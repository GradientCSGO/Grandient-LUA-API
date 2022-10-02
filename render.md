Usage example: https://github.com/EcstasyVip/Ecstasy_LUA_API/blob/main/examples/render_example.lua


In the software there are 3 default fonts:
`"mainfont", "cheatfont1", "cheatfont2" `

`text(float x, float y, color color, int flags, string fontkey , string message)`

`calc_text_size(string text, string fontkey)` returns a vec2

`line(float x1, float y1, float x2, float y2, color color, float thickness)`

`line_gradient(float x1, float y1, float x2, float y2, color color_1, color color_2, float thickness)`

`rect(float x, float y, float w, float h, color color, float rounding)`

`filled_rect(float x, float y, float w, float h, color color, float rounding)`

`filled_rect_gradient(float x, float y, float w, float h, color col_upr_left, color col_upr_right, color col_bot_right, color col_bot_left)`

`arc(float x, float y, float radius, float min_angle, float max_angle, color col, float thickness)`

`triangle(float x1, float y1, float x2, float y2, float x3, float y3, color clr, float thickness)`

`filled_triangle(float x1, float y1, float x2, float y2, float x3, float y3, color clr)`

`circle(float x1, float y1, float radius, color col, int segments, int thickness)`

`circle_filled(float x1, float y1, float radius, color col, int segments)`

`add_poly(vec2 point)`

`poly_line(color col, float thickness)`

`poly_filled(color col)`

`world_to_screen(vec3 in)`  returns vec2

Usage example:

`render.line_gradient(10, 200, 500, 200, color.new(255,0,255,255), color.new(0,0,0,255), 4)`