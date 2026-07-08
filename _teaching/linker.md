---
title: "Static linker"
collection: teaching
type: ""
# permalink: /teaching/2015-spring-teaching-1
venue: "Introduction to Computer Systems (ICS)"
date: 2025-01-01
displaydate: "Spring 2024, Spring 2025, Spring 2026"
# location: "City, Country"
link: "https://github.com/Qcloud1223/ics-ld-public"
excerpt: "An educational x64 Linux static linker"
---

<br>
<br>
Linking is the crossroads of operating systems, compilers, and software engineering,
but it never documented enough on modern Linux systems,
because it appears as a hidden procedure of the compiler.
<br>
<br>

This project is an education-tailered, minimal linker 
which expose the process of 1) combining x64 object files together,
2) matching symbol definition and references, and
3) editing `.text` sections of object files to point to the correct symbol.
<br>
<br>

Together, this project aims to get students familar with
1) C++ programming with provided APIs,
2) relationship between C variables and ELF symbols, and
3) address math and `.text` modification.