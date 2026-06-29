# Spider AI
Simple spider AI with procedural animation

## Description:
Spider has three main states:
- Patrol – roams to random positions within a defined range
- Chase – after detecting the player within detection radius, spider moves toward the player
- Attack – when in attack range, spider deals damage and waits for cooldown before attacking again
Procedural animation is driven by per-leg movement cycles. Each leg dynamically adjusts its position using ground detection and is placed on surrounding terrain while the spider moves, resulting in fully procedural locomotion without baked animations.

## Architecture
- **Unreal Engine 5**
- Scripts are made using **Blueprints**,
- AI is made using **Behaviour Tree**,
- Animation is made using **Control Rig**, **Locomotor** and **Full Body IK**.

## Gameplay:
<img src="images/spider1.gif" width="800"/>
<img src="images/spider2.gif" width="800"/>

## What I’m Learning:
1. Building AI systems using Behavior Trees and Blackboard logic in Unreal Engine 5
2. Implementing procedural animation systems using Control Rig and Full Body IK
3. Designing real-time locomotion systems without using baked animations
4. Combining NavMesh-based AI movement with procedural foot placement systems
