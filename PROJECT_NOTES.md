# KCS Drill Generator - Project Notes

## Project Vision

The KCS Drill Generator is intended to function as a digital instructor rather than a simple random drill generator.

The app should guide beginners, challenge intermediate students, and test advanced students while maintaining a consistent user experience across all systems and drills.

Tutorial features may be added later, but the current focus is on training and skill development.

---

# Standard Color System

## Color Rule

Colors should never change meaning throughout the application.

### Attack / Right Hand (RH)

Color: Red
Hex: #E63C3C

### Left Hand (LH)

Color: Blue
Hex: #3B82F6

### Defense

Color: Amber
Hex: #F5A623

### Counter

Color: Green
Hex: #4CAF50

### Special Moves

Color: Purple
Hex: #A855F7

Examples:

* Abanico
* Sumbrada
* Pluma
* Middle Hanger
* Roof Block
* Special named techniques

### Titles, Categories, Menus, Student Names

Color: White
Hex: #FFFFFF

### Background

Color: Black
Hex: #000000

### Secondary Text / Subtitles

Color: Light Gray
Hex: #999999

Note:
Changed from #555555 after beta tester feedback because some phones displayed the text too dark.

---

# MSi System

## Random Attack Drill

Current existing drill.

Options:

* Number of students
* Known mode
* Secret mode

Added on 

## MSi 15

### Purpose

Randomized angle recognition and reaction training.

### Options

#### Single

Generate one random angle.

Range:
1-15

#### Half Front

Generate eight random angles.

Range:
1-7

Repeats allowed.

#### Half Back

Generate eight random angles.

Range:
8-15

Repeats allowed.

#### Full

Generate fifteen random angles.

Range:
1-15

Repeats allowed.

### Speed Options

#### Slow

* One angle at a time
* Longer pauses
* Designed for beginners

#### Medium

* One angle at a time
* Moderate pauses

#### Fast

* Short pauses
* Occasional bursts of two or three angles
* Designed to challenge reaction speed

### Display Requirements

* Very large numbers
* Bright display
* Easy to read from several feet away
* Designed for use on phone stands during training

---

# Dobletes

## Single Student Mode

Works similarly to MSi 15.

Random Doblete selected.

Training sequence:

1. Attack displayed
2. Pause
3. Defense displayed
4. Counter displayed
5. Next Doblete begins

### Speed Options

Slow

* Long reveal times

Medium

* Moderate reveal times

Fast

* Short reveal times

---

## Multiple Student Mode

Instructor selects display type.

### Attack Only

Display attack sequence only.

### Attack + Defense

Display attack and defense.

### Attack + Counter

Display attack and counter.

### Full

Display attack, defense, and counter.

May be used with Known or Secret modes.

---

# Rotunda

Separate drill category.

## Beginner Mode

1. Display pattern letter
2. Automatic walkthrough begins
3. App presents sequence step-by-step
4. Student follows along

---

## Intermediate Mode

1. Display pattern letter
2. Student performs from memory
3. Help button available
4. Help button reveals sequence step-by-step
5. Student controls pace

---

## Advanced Mode

1. Display pattern letter
2. Student performs from memory
3. Help button available only if needed
4. Student controls review pace

---

## Rotunda Notes

RH = Right Hand

LH = Left Hand

RH and LH movements generally occur nearly simultaneously.

Colon (:) indicates change of sides.

Example:

RH #1, LH #1, RH #1
:
LH #4, RH #4, LH #4

Abanico should always be displayed by name.

Guard positions should be displayed before the sequence begins.

---

# Double Baston

Currently under development.

Additional review and clarification needed before implementation.

Likely to use the same Beginner / Intermediate / Advanced structure developed for Rotunda.

---

# Design Philosophy

The app should behave like an instructor.

Beginners receive guidance.

Intermediate students receive prompts and optional assistance.

Advanced students are tested on memory, recognition, reaction, and recall.

The goal is not simply displaying information.

The goal is developing skill through structured training.

## Update Log
- May 31, 2026: Add project design notes and full system structure documentation.
