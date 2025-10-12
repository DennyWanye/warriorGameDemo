### UE Version: 5.3

for starting the project, need to add resource `ThirdPerson`

and then do some fix on the map, the map is missing blocks when first open

can fix it by:
copy the blocks inside playground folder from `ThirdPersonExampleMap` to `FeatureDevMap`

### To using console command to do the debug:

1. press `~` to open the console

2. type `showdebug abilitysystem` and press Enter


### To show enemy's attribute in debug mode:
1. go to root -> config -> DefaultGame.ini
2. add below code at the front of the file
```
[/Script/GameplayAbilities.AbilitySystemGlobals]
bUseDebugTargetFromHud = true

```

### To show enemy's 
1. press `~` to open the console

2. type `ai.crowd.DebugSelectedActors 1` and press Enter (need to do this everytime when we enter the UE editor)

3. press F8, and select the target AI pawn