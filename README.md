# Type Island
## Unit 13 Gif

<img src="https://user-images.githubusercontent.com/86101798/167067683-2525c500-8f0b-4ac0-9569-4d350c000bbc.gif" width="250" />

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Singleplayer speed-typing based game. Complete typing based challenges to combat monsters and unlock rewards.

### App Evaluation

- **Category:** Game
- **Mobile:** This app would work on a computer but would be a completely different experience due to the change of keyboard. 
- **Story:** The user will "battle" to earn gold to unlock features for their home island. The battle will consist of the user completing typing-related challenges to progress through an endless stream of monsters, earning more gold the longer they survive.
- **Market:** Anyone and everyone. 
- **Habit:** While it may be addictive in the short term as the user battles new monsters and unlocks new features, there will be a point at which they reach an end and there is no current reason to replay the game.
- **Scope:** We will start with a single game mode and limited features for purchase. We may add other game modes and multiplayer functionality in the future.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [x] User can battle monsters via challenges for gold
- [x] By successfully completing a challenge, the user damages the monster. If the user fails, they take damage.
- [X] Challenges get increasingly harder over time, with monsters rewarding more gold as well.
- [X] Upon death gold is rewarded and they return to their hub
- [x] Gold and unlocks are saved across restarts
- [x] User faces an infinite list of random words, which will provide the basis of the challenges
- [x] User sees animated attacks on correct keystrokes


**Optional Nice-to-have Stories**

- [ ] User can purchase new features for their island from the shop
- [ ] Certain words may be in a different text color and will act as powerups if typed correctly
- [ ] Multiply damage done if user has a combo going, which will be based on their speed and accuracy
- [ ] User views tutorial on initial launch
- [ ] User can access settings and stats

### 2. Screen Archetypes

* Home/Hub
   * Buttons to access the settings and shop, as well as go to battle.
   * Pop up menus for the settings and shop.
   * Label indicating the user's total in-game currency.
* Battle Screen (the actual game)
   * Allows the user to complete typing-based challenges to progress through the level and earn in-game currency.
   * Get progressively harder over time.
   * User has three lives which are lost when they fail a challenge.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* N/A

**Flow Navigation** (Screen to Screen)

* 'Adventure' button -> Battle screen
* 'Complete Adventure' button -> Home/Hub Screen


## Wireframes
<img src="https://user-images.githubusercontent.com/86101798/161202931-18f6d66b-255c-4371-89ed-f617c3255fdd.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

### Models

<img width="990" alt="image" src="https://user-images.githubusercontent.com/86101798/161360786-6ac0ff33-59ec-482d-a158-c431c1f1c221.png">

### Networking
* Home Screen
   * (Update/PUT) Update user in game currency
   * (Update/PUT) Update user unlocked rewards
   * (Update/PUT) Update user settings
* Battle Screen (the actual game)
   * (Update/PUT) Update user in game currency
   * (Update/PUT) Update user statistics

## Unit 10 Gif

<img src="https://user-images.githubusercontent.com/86101798/163517284-92a408db-acaa-4797-8fd7-a9c85e06d104.gif" width="250" />
*Multiple features shown are purely for testing purposes

## Unit 11 Gif

<img src="https://user-images.githubusercontent.com/57662868/164583592-3e52a27f-7320-4bbc-b833-1c6fe711c185.gif" width="250" />

## Unit 12 Gif

<img src="https://user-images.githubusercontent.com/86101798/165883890-4b20d769-b8c8-4fd3-949e-a5d9d93934b9.gif" width="250" />
