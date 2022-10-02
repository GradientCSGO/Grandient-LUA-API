The callbacks are as follow:

`on_paint`

`createmove` (before prediction)

`pred_createmove` (post prediction)

`on_event(game_event event)` (events: bullet_impact, weapon_fire, player_death, player_hurt)

`frame_stage`

`menu_items`


How to use a callback in your lua script:

`cheat.register_callback("createmove", functionName)`