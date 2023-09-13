# Mobile-Porting-Guide
how to add the hitbox - go to PlayState.hx and after these lines ```
// if (SONG.song == 'South')
// FlxG.camera.alpha = 0.7;
// UI_camera.zoom = 1;``` or after the stuff is set to camHud write 
```var hitBox:mobile.HitBox = new mobile.HitBox();
add(hitBox);```
