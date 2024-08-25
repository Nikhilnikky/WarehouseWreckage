# WarehouseWreckage

Developed with Unreal Engine 5

UE 5:
Physics :
Simuate -> To move when collision
Enable gravity -> Gravity(fall down)
The greater the mass, the greater the collision effect on other objects
Impulse == move a object(eg: on button click)
Force = mass*acc
Impulse = mass*velocity

X axis --> RIGHT
Y axis --> LEFT DOWNWARD
Z axis --> UP

addImpulse function:
when Vel change is true, u hv to apply small value, when false it will take mass into consideration, so u hv to apply more value

Ctrl+space to open content drawer

SpawnActor :
inputs :getPlayerPawn,getActorLocation,getControlRotation

AddImpulse:
inputs :getActorForwardVector*float

dont use scale option under transform, instaead use brush dimensions

when u want to add child to a actor, add it in details panel under static mesh component, not to static mesh actor in outliner

when u enable simulate physics to any mesh, and it is unstable while playing(moving by itself), go to that mesh and remove collsion and add 10DOP Z simplified collision

version control for UE5 :
download Git
dowlnload git LFS
download github desktop
goto git bash, type "git lfs install"

if condition === branch
