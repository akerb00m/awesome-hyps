# Place🌀

A teleport destination. It works similarly to hyperfy v1 place app.
Allowing players teleport to a location using `Portal🌀` or `Sphere🌀`
Can also use `/<PLACE_NAME>` to teleport to a place.

## Features

- built in /command
- easily see where places have been placed with `inWorld` UI
- hide mesh but still active

## How to use

- Place **.hyp** `inWorld`
- Set a Place name/destination in the inspector

# Portal🌀

Portal🌀 allows players to teleport to a location.

## Features

- onTriggerEnter() which teleports player to a **set place**
- show/hide :
	- portal name
	- portal visibility 
	- portal rim
- Tweak portal rim speed / emissive intensity

## How to use

- Place **.hyp** `inWorld`
- Set a Portal name/destination in the inspector

# Sphere🌀

Sphere🌀 allows players to collide with a volume and teleport to a location.

## Features

- onTriggerEnter() which teleports
- hide mesh but trigger still active

## How to use

- Place .hyp `inWorld`
- Set a Portal name/destination in the inspector