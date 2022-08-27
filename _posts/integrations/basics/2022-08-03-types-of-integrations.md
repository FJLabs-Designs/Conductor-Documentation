---
title: Types of integrations - Keycodes vs MIDI
subtitle: Learn about the two different types of integration available on Conductor.
categories: [integrations, basics]
---

Conductor features two types of operating modes to integrate with your professional applications: keycodes and MIDI. Conductor can use either mode simultaneously or mix and match between them seamlessly.

### Keycodes vs MIDI

In keycode operating mode, each function (encoder press, turn, key press) is programmed to act like keyboard keycode. As well, each keycode can also contain an arbitrary combination of codes (such as holding modifier keys like Shift and Control) or a "macro" of keys.

In MIDI operating mode, each function is programmed to act like a dedicated MIDI controller. MIDI control allows for interaction with applications that support the MIDI codec and often offer deeper integration (such as adjusting slider position) than normal keycodes. 

Each function can be swapped to a different mode independently of one another, so you can have one key in Keycode mode and another in MIDI mode at the same time.

### When to use Keycodes or MIDI

In general, most applications work best in Keycode mode. If you can interact with your application using your keyboard through traditional keyboard shortcuts, then Keycode mode would be the correct mode to choose. Keycode mode can emulate any existing keyboard shortcut and can also perform complex repeated keyboard interactions like pushing one shortcut after another.

[Learn more about Keycode Mode](/integrations/basics/using-keycodes/)

If you are working with a more media-centric application like Premiere Pro, Lightroom, or FL Studio, you may choose to assign certain functions to MIDI. This may potentially allow you to interface deeper with your application where there is no existing keyboard shortcut or may allow Conductor to act as a "virtual instrument" in audio applications.

[Learn more about MIDI Mode](/integrations/basics/using-MIDI/)