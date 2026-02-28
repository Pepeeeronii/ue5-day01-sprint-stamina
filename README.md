# UE5 Day 01 — Sprint + Stamina + UI (Blueprint)

## What I built
- Sprint toggle (Enhanced Input, Left Shift)
- Stamina drain while sprinting + auto stop at 0
- Stamina regeneration (when not sprinting)
- UI stamina bar (UMG ProgressBar) synced with Stamina / MaxStamina

## Controls
- Move: WASD
- Sprint: Left Shift

## Tech details
- Blueprint-only implementation (BP_ThirdPersonCharacter)
- Data: variables (Stamina, MaxStamina, DrainRate, RegenRate, WalkSpeed, SprintSpeed)
- UI: WBP_HUB updates PB_Stamina Percent every tick using PlayerRef

## How to run
1. Open `DAY1.uproject` in Unreal Engine 5
2. Press Play
3. Hold Left Shift to sprint and drain stamina

## Screenshots / Video
- Add screenshots here (recommended)
- Add a short gameplay clip (recommended)
