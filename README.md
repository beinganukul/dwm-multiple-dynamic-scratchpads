# dwm-scratchpad

Patch to enable 3 separate scratchpad using three separate keybindings. this work is based on [GasparVardanyan's](https://gitlab.com/GasparVardanyan/dwm-scratchpad) patch.

## why?
for my liking i wanted 3 separate keybindings for separate windows and that too needed to be created dynamically.

## default bindings(config.def.h)
- MODKEY, XK_s, MODKEY, XK_y, MODKEY, XK_u - <i> scratchpad_show </i>
- MODKEY|Shiftmask, XK_s, MODKEY|Shiftmask, XK_y, MODKEY|Shiftmask, XK_u - <i> scratchpad_hide </i>
- MODKEY|ShiftMask, XK_r - scratchpad_remove

## this patch conflicts with gaspar's patch

## todo
publish it to suckless website.

