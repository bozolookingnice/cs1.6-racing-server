# AMXX API Contract

This document defines the allowed interfaces between AMXX plugins and the
CS 1.6 Racing game mode. All AMXX code MUST comply with this contract.

## Allowed Includes

Only the following global includes may be used:

- amxmodx
- amxmisc
- fakemeta
- hamsandwich
- xs

Direct use of engine.inc is forbidden outside movement implementation.

## Racing API

The following custom includes define the ONLY public API:

- racing/constants.inc
- racing/movement.inc
- racing/vehicle.inc
- racing/checkpoints.inc

## Ownership Rules

- Only racing_movement.sma may read or write pev_velocity
- Only racing_movement.sma may register PlayerPreThink hooks
- No plugin may modify gravity, friction, or maxspeed directly
- No plugin may call engfunc() or dllfunc() outside movement

## Movement API Example

Plugins must NOT manipulate player velocity directly.

Correct usage:

```pawn
racing_apply_accel(id, dt);
racing_apply_steer(id, dt);
racing_apply_limits(id);
set_pev(id, pev_velocity, vel); // forbidden
```

## Forbidden Practices

- Direct fakemeta calls outside movement module
- Writing to pev_velocity from multiple plugins
- Using undocumented natives
- Inventing helper functions not declared in racing/*.inc
- Copy-pasting code from other mods

## AI Usage Rules

When generating AMXX code using AI:

- Provide only the racing/*.inc files
- AI must use only declared APIs
- If an API is missing, create an issue instead of guessing
- All AI-generated code must compile without warnings
