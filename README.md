This is an edit of https://steamcommunity.com/sharedfiles/filedetails/?id=407236638&searchtext=fading+door]

This version of the fading door tool intends to make it more fun to play against in a PVP setting. The main changes are listed below:

  [*]Open, Close, and Active sounds are now required (as long as the sounds load). Players now have an audio cue for fading door activities
  
  [*]They cannot be shot through by default anymore, though this can be enabled

  [*]Doors have a delay between when the key to open is pressed and when it actually opens. During this time, the door glows blue to signify it is about to open.

  [*]Doors have a delay between when the key to open is let go of and when the door actually closes. During this time, the door glows yellow to signify it is about to close. 

Specific values and colors can be changed, using the following convars:

fading_door_nokeyboard: whether player input directly from keyboard is allowed

fading_door_bulletspassable: whether bullets will pass through the fading door

fading_door_startingphase_length: how long the starting (default color blue) phase lasts

fading_door_startingphase_success_r. fading_door_startingphase_success_g, fading_door_startingphase_success_b: color when user is currently opening the door

fading_door_startingphase_fail_r, fading_door_startingphase_fail_g, fading_door_startingphase_fail_b: color components of the color when user tries to open door but then lets go of the key before it opens

fading_door_endingphase_length: how long the ending (default color yellow) phase lasts

fading_door_endingphase_r, fading_door_endingphase_g, fading_door_endingphase_b: color components of the ending phase when the door is about to close

fading_door_phase_opacity: opacity of the colors during either phase

fading_door_material_string: the material used when in either of the phases
