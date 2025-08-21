---
layout: default
parent: Field Opcodes
title: 056_SPUREADY
permalink: /technical-reference/field/field-opcodes/056-spuready/
---

-   Opcode: **0x056**
-   Short name: **SPUREADY**
-   Long name: SPU Start

#### Argument

none

#### Stack

  
*0*

**SPUREADY**

#### Description

Sets the asynchronous timer to 0 frames. See [SPUSYNC](164_SPUSYNC) for details.

SPU is the sound processing unit on the PS1. This is used to ready the timer. SPUSYNC is used to synchronise with audio playback. This is used in the Eyes on Me scene to sync game dialogue to the song.
