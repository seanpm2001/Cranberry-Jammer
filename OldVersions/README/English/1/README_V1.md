
***

<img src="/Cranberry_Jammer_1024pxIcon_V1_HighCompression.png" alt="Cranberry Jammer logo" width="256" height="256">

# [Cranberry Jammer](#Cranberry-Jammer)

`⚡️📻️⚡️📡️ Cranberry Jammer is a hardware project for creating signal jammers. It also develops the CranberryOS project.`

***

## [Legal notice](#Legal-notice)

In most countries, it is illegal for civilians to possess signal jammers. This software is intended for use on hardware contracted to law enforcement and other permitted users.

So far, no contracts have been made for this project (as of 2023, Tuesday, June 27th) it will likely be a long time before one is made.

<!--
Legality

I cannot produce this device without a legal contract, due to it being illegal for civilians to possess signal jammers. Even then, I don't have enough money to build one of these for myself, and wouldn't have much use for it.
!-->

***

## [Native devices](#Native-devices)

The devices that are the core of this project have not yet been developed.

**Devices**

- [:octocat: `cb49n1j1`](https://github.com/seanpm2001/Cranberry-Jammer#cb49n1j1)

> Regular variant (cb49n1j1)

> > A red, portable signal jammer on wheels, estimated to cost somewhere between $4000 and $14000 (in 2023, May 6th money)

- [:octocat: `cb49b1j1`](https://github.com/seanpm2001/Cranberry-Jammer#cb49b1j1)

> Bulletproof variant (cb49b1j1)

> > Costs about 8-10x more, but is bulletproof, and partially blast resistant. It is the same signal jammer, but the mount has heavy armor equivalent to a mini tank. Tracks instead of wheels are an optional feature for all-terrain usage. 

***Codes:***

- cb = cranberry jammer
- 49 = radius
- n1 = normal A
- j1 = Jammer A
- b1 = Bulletproof A

> **Note** _Batteries sold separately (for now)_

***

## [Operating System](#Operating-System)

Cranberry Jammer devices run CranberryOS, a specialized Linux/TinyOS distribution that uses less than 90 megabytes of RAM (64 bit) and less than 180 megabytes of RAM (128 bit) and is optimized to perform all functions required for the device.

For more information, see: [:octocat: `CranberryOS`](https://github.com/seanpm2001/CranberryOS/)

***

## [Slogans](#Slogans)

> A signal jammer vs. a cellular world

> The main line of defense against a cellular world

> Portable signal jammer machine

***

## [Frequencies](#Frequencies)

The signal jammer is currently designed to target the following frequency levels:

- 2.4 GhZ
- 5.0 GhZ
- Other/unspecified

***

## [Radius](#Radius)

Through the operating system, you can adjust the radius of the signal jammer between 6 levels (for [cb49](#Native-devices) models only)

- Level 0: Off (0 meters) (0.00 feet) (nowhere)
- Level 1: On (3 meters) (9.84 feet) (all angles)
- Level 2: On (6 meters) (19.68 feet) (all angles)
- Level 3: On (9 meters) (29.52 feet (all angles))
- Level 4: On (12 meters) (39.37 feet) (all angles)
- Level 5: On (15 meters) (49.21 feet) (all angles)

***

## [Structure description](#Structure-description)

Blueprints are not yet available, so this textual description is provided for cb49 models:

- Device rolls around, a metal base with 1 monitor on each side (4 total) (the monitors are optional, you really only need 1)
- Signal jammer is behind the monitors, controls are just below each screen

***

## [Controls](#Controls)

The following hardware controls are present:

- On/off
- Frequency types
- Level +
- Level -
- Keyboard (optional, USB can be used as an alternative)

***

## [Charging](#Charging)

The device is solar powered, do not cover the top of the device for long periods of time during use. It also has several removable batteries, with up to 150000 mAh in reserves (depending on how many batteries you add) minimum: 1, maximum: 100

***

## [Warnings](#Warnings)

This device is indiscriminate. It will attack/disrupt any wireless network connection within its set range, with no possibility for exclusions.

This device may cause damage to the devices receiving the wireless connection. I would like to work on reducing this if possible.

***

## [Deployment types](#Deployment-types)

Deployment formations for effective usage:

### [Drone sky enforcer](#Drone-sky-enforcer)

Place 4 cb49s on a 4 story platform, one per platform, to enforce a 60 meter no-drone zone

### [Gridfree I](#Gridfree-I)

Place cb49s all around a property, each one 3 to 15 meters apart, to create a dead zone around a property, separating it from the grid.

***

## [Why call it Cranberry?](#Why-call-it-Cranberry)

Of the 5 berries I have eaten in my life, cranberries are my least favorite, and it is one of the few berries that don't have any major software projects associated with it (unlike Raspberry Pi or BlackberryOS) cranberries are sour, and this device would sour the relations of those who possess it.

***

## [Original draft](#Original-draft)

```plain-text
Cranberry Jammer

Slogans:

A signal jammer vs. a cellular world
The main line of defense against a cellular world

Portable signal jammer machine

Frequencies:

2.4 GhZ, 5.0 Ghz, other

Radius levels

Level 0: Off (0 meters) (0.00 feet) (nowhere)
Level 1: On (3 meters) (9.84 feet) (all angles)
Level 2: On (6 meters) (19.68 feet) (all angles)
Level 3: On (9 meters) (29.52 feet (all angles))
Level 4: On (12 meters) (39.37 feet) (all angles)
Level 5: On (15 meters) (49.21 feet) (all angles)

Device rolls around, a metal base with 1 monitor on each side (4 total)
Signal jammer is behind the monitors, controls are just below each screen

Controls

On/off
Frequency types
Level +
Level -

Charger
Solar powered, solar comes from the top
Several removable batteries, up to 150000 mAh (depending on how many batteries you add) minimum: 1, maximum: 100

Legality

I cannot produce this device without a legal contract, due to it being illegal for civilians to possess signal jammers. Even then, I don't have enough money to build one of these for myself, and wouldn't have much use for it.

Warnings

This device is indiscriminate. It will attack/disrupt any wireless network connection within its set range, with no possibility for exclusions.

This device may cause damage to the devices receiving the wireless connection. I would like to work on reducing this if possible.

Operating system: CranberryOS

Deployment types:

Drone sky enforcer

Place 4 cb49s on a 4 story platform, one per platform, to enforce a 60 meter no-drone zone

Gridfree I

Place cb49s all around a property, each one 3 to 15 meters apart, to create a dead zone around a property, separating it from the grid.

Why call it Cranberry?

Of the 5 berries I have eaten in my life, cranberries are my least favorite, and it is one of the few berries that doesn't have any major software associated with it (unlike Raspberry Pi or BlackberryOS) cranberries are sour, and this device would sour the relations of those who possess it.

Variants

Codes:

cb = cranberry jammer
49 = radius
n1 = normal A
j1 = Jammer A
b1 = Bulletproof A

Regular variant (cb49n1j1)
A red, portable signal jammer on wheels, estimated to cost somewhere between $4000 and $14000 (in 2023, May 6th money)

Bulletproof variant (cb49b1j1)
Costs about 8-10x more, but is bulletproof, and partially blast resistant. It is the same signal jammer, but the mount has heavy armor equivalent to a mini tank. Tracks instead of wheels are an optional feature for all-terrain usage.

Note: batteries sold separately

```

***

## [Documentation](#Documentation)

Additional documentation is available [:octocat: `in a separate repository`](https://github.com/seanpm2001/Cranberry-Jammer_Docs/)

***

# [File info](#File-info)

**File version:** `1 (2023, Wednesday, June 28th at 10:53 pm PST)`

***

# [Footer](#Footer)

You have reached the end of this page.

###### [EOF](#EOF)

***
