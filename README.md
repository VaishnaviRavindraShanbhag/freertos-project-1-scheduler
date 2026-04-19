# FreeRTOS Scheduler Modification on Arduino Mega

## Overview

This project focused on understanding and extending the FreeRTOS scheduler through hands-on kernel modification and real-time task execution analysis on the Arduino Mega 2560.

I implemented periodic task scheduling, analyzed runtime behavior, and modified core scheduler logic to change how task priorities were selected during execution.

## What I Implemented

- Created multiple periodic real-time tasks with different priorities and execution rates
- Used Serial Monitor logging to trace scheduling decisions and runtime behavior
- Modified the FreeRTOS kernel (`tasks.c`) to reverse default priority-based task selection
- Verified custom scheduler behavior through controlled experiments and execution traces
- Analyzed idle task execution and system timing behavior

## Key Technical Concepts Demonstrated

- RTOS task creation using `xTaskCreate()`
- Periodic scheduling using `vTaskDelay()`
- Priority-based preemptive scheduling
- Kernel-level scheduler customization
- Real-time debugging through runtime logs
- Task state transitions and idle task handling

## Tech Stack

- Embedded C
- FreeRTOS v10.4.3-6
- Arduino Mega 2560
- Arduino IDE / Serial Monitor

## Why Code Is Not Public

Some base kernel files, framework structure, and starter materials were provided as part of university coursework.  
To respect academic policies, this repository serves as a project showcase with documentation of my original modifications, design understanding, and implementation work.

## Outcome

This project gave me strong practical experience with RTOS internals, scheduling algorithms, and embedded debugging—skills directly relevant to firmware and embedded systems engineering roles.
