# Vibrant vehicle handling structure

- All of the below values are what we've chosen to help diversify our car classes, giving players a clear distinction between "high" & "low" quality vehicles
- You don't have to follow it but we feel it will help you keep stuff more balanced overall

--X Class:-- 
- fInitialDragCoeff: > 3.0
- fDownforceModifier: > 1.0 
- fInitialDriveForce: 0.36 < 0.40
- fInitialDriveMaxFlatVel: 200 < 210
- fBrakeForce: 1.0 < 1.4
- fTractionCurve: 2.1 < 2.8
- fSuspensionForce: 2.2 < 2.8
- fSuspensionReboundDamp: 0.8 >

-----------------------------------------------------------------------------

--S Class:-- 
- fInitialDragCoeff: > 3.0
- fInitialDriveForce: 0.295 < 0.32
- fInitialDriveMaxFlatVel: 180 < 190
- fBrakeForce: 1.0 < 1.3
- fTractionCurve: 1.9 < 2.4
- fSuspensionForce: 2.2 < 2.7
- fSuspensionReboundDamp: 0.8 >

--S Vintage:-- 
- fInitialDragCoeff: > 3.0
- fInitialDriveForce: 0.275 < 0.3
- fInitialDriveMaxFlatVel: 180 < 190
- fBrakeForce: 1.0 < 1.3
- fTractionCurve: 1.9 < 2.3
- fSuspensionForce: 2.1 < 2.4
- fSuspensionReboundDamp: 0.8 >

-----------------------------------------------------------------------------

--A Class:-- 
- fInitialDragCoeff: > 3.5
- fInitialDriveForce: 0.23 < 0.275 (-0.02 for AWD)
- fInitialDriveMaxFlatVel: 180
- fBrakeForce: 1.0 < 1.2
- fTractionCurve: 1.9 < 2.4
- fSuspensionReboundDamp: 0.6 < 0.8

--A Vintage:-- 
- fInitialDragCoeff: > 3.5
- fInitialDriveForce: 0.23 < 0.255 (-0.02 for AWD)
- fInitialDriveMaxFlatVel: 175
- fBrakeForce: 0.9 < 1.0
- fTractionCurve: 1.9 < 2.1
- fSuspensionReboundDamp: 0.6 < 0.8

--A Off-Road:-- 
- fInitialDragCoeff: > 3.5
- fInitialDriveForce: 0.23 < 0.255 (-0.02 for AWD)
- fInitialDriveMaxFlatVel: 170
- fBrakeForce: 0.9 < 1.1
- fTractionCurve: 1.9 < 2.1
- fTractionLossMult: 0.10 < 0.40
- fSuspensionReboundDamp: 0.6 < 0.8

---------------------------------------------------------------------------

--B Class:-- 
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.20 < 0.23
- fInitialDriveMaxFlatVel: 170
- fBrakeForce: 0.8 < 1.0
- fTractionCurve: 1.8 < 2.2
- fSuspensionReboundDamp: > 0.6

--B Vintage:-- 
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.20 < 0.22
- fInitialDriveMaxFlatVel: 165
- fBrakeForce: 0.8 < 0.90
- fTractionCurve: 1.8 < 1.9
- fSuspensionReboundDamp: > 0.6

--B Off-Road:-- 
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.20 < 0.22
- fInitialDriveMaxFlatVel: 160 > 165
- fBrakeForce: 0.8 < 1.0
- fTractionCurve: 1.75 < 2.0
- fTractionLossMult: 0.10 < 0.50
- fSuspensionReboundDamp: > 0.95

--B Rally:-- 
- fInitialDragCoeff: 6.0
- fInitialDriveForce: 0.45 < 0.50
- fInitialDriveMaxFlatVel: 120
- fClutchChangeRateScaleUpShift/DownShift: 6.0
- fBrakeForce: 0.70
- fTractionCurve: 1.50 < 1.80
- fTractionLossMult: 0.40 < 0.80
- fSuspensionReboundDamp: > 0.80

-----------------------------------------------------------------------------

--C Class:--
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.17 < 0.20
- fInitialDriveMaxFlatVel: 155 > 160
- fBrakeForce: 0.6 < 0.8
- fTractionCurve: 1.6 < 2.0
- fSuspensionReboundDamp: > 0.6

--C Vintage:--
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.17 < 0.18
- fInitialDriveMaxFlatVel: 145 > 150
- fBrakeForce: 0.6 < 0.7
- fTractionCurve: 1.5 < 1.9
- fSuspensionReboundDamp: > 0.6

--C Off-Road:--
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.17 < 0.18
- fInitialDriveMaxFlatVel: 140 > 150
- fBrakeForce: 0.6 < 0.7
- fTractionCurve: 1.5 < 1.8
- fTractionLossMult: 0.10 > 0.50
- fSuspensionReboundDamp: > 0.6

------------------------------------------------------------------------------

--D Class:--
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: < 0.17
- fInitialDriveMaxFlatVel: 100 > 140
- fBrakeForce: < 0.6
- fTractionCurve: < 1.7
- fSuspensionReboundDamp: > 0.6

------------------------------------------------------------------------------

--Motorcycle:--

--X Class Bikes:-- (Not including "fun" bikes)
- fInitialDragCoeff: > 4.0
- fInitialDriveForce: 0.31 < 0.35
- fDriveInertia: 1.0
- fInitialDriveMaxFlatVel: 170 - 180
- fSteeringLock: 20-30
- fTractionCurve: 1.9 < 2.35
- Lean values dependant on motorcycle type

--S Class Bikes:--
- fInitialDragCoeff: 5.0
- fInitialDriveForce: 0.295 < 0.32
- fDriveInertia: 1.0
- fInitialDriveMaxFlatVel: 150 - 160
- fSteeringLock: 20-30
- fTractionCurve: 1.8 < 2.2
- Lean values dependant on motorcycle type

--A Class Bikes:--
- fInitialDragCoeff: 6.0
- fInitialDriveForce: 0.23 < 0.275
- fDriveInertia: 1.0
- fInitialDriveMaxFlatVel: 130 - 140
- fSteeringLock: 20-30
- fTractionCurve: 1.7 < 2.0
- Lean values dependant on motorcycle type

--Chopper Class Bikes:--
- fInitialDragCoeff: 6.0 < 8.0
- fInitialDriveForce: 0.30 < 0.325
- fDriveInertia: 1.0
- fInitialDriveMaxFlatVel: 150 - 160
- fSteeringLock: 15-25
- fTractionCurve: 1.5 < 1.85
- Lean values dependant on motorcycle type

--Off-road Class Bikes:--
- fInitialDragCoeff: 7.0 - 9.0
- fInitialDriveForce: 0.25 < 0.30
- fDriveInertia: 1.0
- fInitialDriveMaxFlatVel: 55 - 65
- fSteeringLock: 35-40
- fTractionCurve: 1.6 < 1.85
- Lean values dependant on motorcycle type

------------------------------------------------------------------------------


# Listed below are some of the core components and points to understand what we've done in the process of creating this

- All vehicles use the handlingFlag `800000` _HF_INCREASED_GRAVITY - This attempts to prevent vehicles from curb boosting and double clutching

- Anyone unsure what each flag does can go to https://adam10603.github.io/GTA5VehicleFlagTool/ to understand and adjust if wanted

- All of the Boosting, Event, Job and Lorefriendly vehicles have seperate folders and a Class system in the data folder

- Almost all of the add on vehicles have had their textures optimised

- Props to the creators of the vehicles we have in the packs - maybe say we will remove them if this is an issue etc?

- Inside the vehiclehandling folder is ['handling]; this covers all the vanilla vehicles that I've edited but not ALL that is in the game.
Within that file I've seperated all classes based on the same class systems within each data folder - Using search for e.g `A Class` Will bring you to the corresponding class

- The carcols, carvariations and vehicle(meta) files are edits either to prevent weapons on cars or other things that may not be wanted on a FiveM RP server
If they are not useful for you, simply delete them and the base game will take over from there