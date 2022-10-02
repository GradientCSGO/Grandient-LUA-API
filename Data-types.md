# frame_stage
Type: enumeration

Possible Values:
* `FRAME_UNDEFINED`
* `FRAME_START`
* `FRAME_NET_UPDATE_START`
* `FRAME_NET_UPDATE_POSTDATAUPDATE_START`
* `FRAME_NET_UPDATE_POSTDATAUPDATE_END`
* `FRAME_NET_UPDATE_END`
* `FRAME_RENDER_START`
* `FRAME_RENDER_END`

# hitbox

Type: hitbox id enumeration

Possible Values:
* `head`
* `neck`
* `pelvis`
* `stomach`
* `lower_chest`
* `chest`
* `upper_chest`
* `right_thigh`
* `left_thigh`
* `right_shin`
* `left_shin`
* `right_foot`
* `left_foot`
* `right_hand`
* `left_hand`
* `right_upper_arm`
* `left_upper_arm`
* `right_lower_arm`
* `left_lower_arm`

# weapon_type

Type: weapon_type enumeration

Possibe Values:
* `default`
* `autosniper`
* `scout`
* `awp`
* `rifle`
* `pistol`
* `heavy_pistol`

# color
Type: color structure
* `.new(int r, int g, int b, int a)`

Getters

* `:r` 
* `:g`
* `:b`
* `:a`

Setters

* `:setred(int r)`
* `:setgreen(int g)`
* `:setblue(int b)`
* `:setalpha(int a)`

# vec3
Type: 3 point vector structure 
* `.new(float x, float y, float z)`

Fields

* `.x` 
* `.y`
* `.z`

Functions

* `:length()` returns float
* `:length2d()` returns float
* `:length_sqr()` returns float
* `:clamp()`
* `:normalize()`
* `:distance(vec3 otherVec)` returns float
* `:to_angle()` returns vec3

# vec2
Type: 2 point vector structure 
* `.new(float x, float y)`

Fields

* `.x` 
* `.y`

Functions

* `:length()` returns float

# usercmd
Type: user command

Fields

* `.cmd_number` 
* `.tick_count`
* `.viewangles`
* `.aimdirection`
* `.forwardmove`
* `.sidemove`
* `.upmove`
* `.buttons`
* `.impulse`
* `.weaponselect`
* `.weaponsubtype`
* `.random_seed`
* `.mousedx`
* `.mousedy`
* `.predicted`

# client_class
Type: client class

Fields

* `.class_id` 
* `.name`

# cbaseentity
Type: entity class

Functions

* `:origin()`  returns vec3
* `:velocity()` returns vec3
* `:name()` returns string
* `:index()` returns int
* `:flags()` returns int
* `:health()` returns int
* `:movetype()` returns int
* `:client_class()` returns client_class
* `:team()` returns int
* `:is_player()` returns bool
* `:eye_angles()` returns vec3
* `:mins()` returns vec3
* `:maxs()` returns vec3
* `:is_enemy(cbaseentity to)` returns bool
* `:get_prop_int(string table, string prop)` returns int
* `:get_prop_fl(string table, string prop)` returns float
* `:get_prop_b(string table, string prop)` returns bool
* `:get_prop_fl(string table, string prop)` returns float
* `:get_prop_vec(string table, string prop)` returns vec3
* `:set_prop_int(string table, string prop, int value)`
* `:set_prop_fl(string table, string prop, float value)`
* `:set_prop_b(string table, string prop, bool value)`
* `:set_prop_vec(string table, string prop, vec3 value)`

# player_info
Type: info about player

Fields:
* `.xuidLow` -> int
* `.xuidHigh` -> int
* `.name` -> string
* `.userid` -> int
* `.isteamid` -> int
* `.friends_name` -> string
* `.fakeplayer` -> bool
* `.is_hltv` -> bool


# game_event
Type: game event type

Functions
* `:get_name()`
* `:get_int(const char* keyname = nullptr)`
* `:get_float(const char* keyname = nullptr)`
* `:get_bool(const char* keyname = nullptr)`
* `:get_string(const char* keyname = nullptr)`
