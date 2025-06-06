# is_key_down `0xAC93D58A`

Checks if a key is currently being held down. You can find the list of usable keycodes [here](https://docs.rdrmp.redmods.com/#/page/game_reference/keyboard_keycodes).

> [!TIP]
> This function supports two input types: a numeric keycode or a string representation of the key (e.g. "F5" or 63).

```lua
natives.extended.is_key_down(_keycode --[[ number/string ]])
```

---

#### 💡Example Usage

```lua
-- Using a string representation
if natives.extended.is_key_down("F5") then

    print("F5 (Id 63) key is currently being held down!")
end
```

```lua
-- Using a numeric keycode
if natives.extended.is_key_down(63) then

    print("F5 (Id 63) key is currently being held down!")
end
```
