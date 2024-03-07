# Mobile-Porting-Guide
don't use this unfinished and kinda broken

how to add the hitbox - go to PlayState.hx and after these lines 
```
// if (SONG.song == 'South')
// FlxG.camera.alpha = 0.7;
// UI_camera.zoom = 1;
```
or after the objects get set to the camHUD (like this)
```
doof.cameras = [camHUD];
```
write v

```
var hitBox:mobile.HitBox = new mobile.HitBox();
add(hitBox);
```
