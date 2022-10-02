These functions are to be called in the "menu_items" callback.
for proper implementation look at this example: https://github.com/EcstasyVip/Ecstasy_LUA_API/blob/main/examples/menuItems.lua

`checkbox(string label, bool variable)` returns bool

`slider(string label, float variable, float min, float max, string format, float power)` returns float

`text(string txt)`

`separator()`

`combo(string label, int cur_item, string items)` returns int

`color_picker(string label, color clr)` returns color

`spacing()`
 
`input_text(string label, string text)` returns string

`button(string label, vec2 size)` returns bool

***
KEYBINDS
`register_keybind(string keybindname)` - registers your keybind in the system, call once outside of any callback

**keybindname must be unique, otherwise it wont register**

`render_keybind(string label, string keybindname)` - call in menu_items, draws the keybind menu item with your desired label

`keybind_state(string keybindname)` returns bool - call wherever, gives you the current state of your desired keybind




