\# FreeRTOS Project 1 – Scheduler Modification



\## Overview

This project explores FreeRTOS task scheduling on an Arduino Mega, including

task creation, periodic execution, and kernel-level scheduler modification.



\## What I Implemented

\- Created periodic FreeRTOS tasks with different priorities and periods

\- Added Serial Monitor logging to trace task execution

\- Modified the FreeRTOS kernel scheduler to reverse priority selection

\- Verified behavior using runtime output



\## Key Technical Work

\- FreeRTOS task creation (`xTaskCreate`)

\- Periodic execution using `vTaskDelay`

\- Kernel modification in `tasks.c`

\- Priority handling and idle task behavior



\## Tech Stack

\- C

\- FreeRTOS (v10.4.3-6)

\- Arduino Mega 2560



\## Notes

Base FreeRTOS kernel files and headers were provided as part of university coursework.

This repository contains documentation and original work only - with only snippets of modifies code provided



