# Platformer

2D platformer prototype built in **Unity 6** (6000.0.32f1).

## Features
- Player controller with ground/wall detection (`PlayerController`, `TouchingSpaceDirections`)
- Enemy with detection zones and attacks (`Enemy`, `DetectionZone`, `Attck`)
- Damage and health system (`Damageble`)
- Animator state machine behaviours (`SetBoolBehavior`, fade-out on death in `FadeRomveBehaviour`)
- Parallax background (`ParallaxEffect`)

## How to run
1. Clone the repository.
2. Open the folder in Unity Hub with Unity 6000.0.32f1 or newer.
3. Open `Assets/Scenes/Gameplay scene` and press Play.

## Structure
```
Assets/Scripts/   gameplay scripts
Assets/Scripts/Statemachine/   animator behaviours
```
