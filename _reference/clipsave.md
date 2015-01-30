---
layout: page
title: CLIPSAVE statement
---

Write program to clipboard.


## Syntax Diagram

![Syntax diagram](/diagram/CLIPSAVE-statement.png)


## Also See

- [SAVE statement](/reference/save)


## Details

This is similar to the [SAVE](/reference/save) or [LIST](/reference/list) statements, except the program is written to the system clipboard.  This allows the user to copy a program to another app by running `CLIPSAVE` and then using the Paste command in the other app.


## Examples

    REM Load program from file then put it on clipboard
    LOAD "myprogram.bas"
    CLIPSAVE