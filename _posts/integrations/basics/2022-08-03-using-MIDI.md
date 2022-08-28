---
title: Using MIDI Mode
subtitle: Learn about the various features of MIDI mode
categories: [integrations, basics]
---

### Table of Contents
{:.no_toc}
* TOC
{:toc}

Conductor is able to operate as a basic generic MIDI device to allow deeper control of certain professional applications. Conductor can utilize QMK MIDI features through VIA as well as 18 proprietary MIDI codes assigned to generic CC values.

### What is MIDI

MIDI (Musical Instrument Digital Interface) is a communication protocol that is used commonly for musical instruments, digital mixers, and other audio production equipment. Conductor uses MIDI's powerful protocol to send two types of MIDI messages: `Control Change` and `Note ON/OFF`. 

#### Control Change Messages

Control Change, or CC, messages consist of a "Control Change Message" and a value between 0 and 127. Typically each MIDI CC Message is reserved for a ['specific predefined function](https://anotherproducer.com/online-tools-for-musicians/midi-cc-list/) such as a Foot Pedal or a Pan effect. However, there are certain generic CC Messages that have been left undefined and available for use with generic controllers. Conductor uses the following MIDI Control Change Messages for **knob controls**:

| MIDI Assignment | CC Message |
|-----------------|------------|
| `A_CW/_CCW` | 46 |
| `B_CW/_CCW` | 47 |
| `C_CW/_CCW` | 48 |
| `D_CW/_CCW` | 49 |
| `E_CW/_CCW` | 50 |
| `F_CW/_CCW` | 51 |

{% include alert.html style="success" text='Knob control using MIDI (rotation) operates on a "twos complement" basis. That is, a clockwise rotation is set to a value of 1 and counterclockwise 127. Ensure your companion apps recognize "twos complement" encoding.' %}

As well, Conductor can assign Control Change messages to **pressing** the knob. Knob presses send a value of 127 while pressed and a value of 0 when released on the following Control Change Messages:

| MIDI Assignment | CC Message |
|-----------------|------------|
| `A Press` | 80 |
| `B Press` | 81 |
| `C Press` | 82 |
| `D Press` | 83 |
| `E Press` | 84 |
| `F Press` | 85 |

#### Note On/Off

Conductor can also use QMK's Note On/Off MIDI controls. *Documentation for this is currently in progress.*

### Using MIDI

*Documentation coming soon.*