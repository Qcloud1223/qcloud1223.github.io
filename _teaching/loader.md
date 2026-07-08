---
title: "Dynamic loader"
collection: teaching
type: "Undergraduate course"
venue: "Operating systems, Introduction to Computer Systems (ICS)"
date: 2023-01-01
displaydate: "Fall 2022, Spring 2023"
link: "https://github.com/Qcloud1223/COMP461905"
excerpt: "An educational x64 ELF dynamic loader"
---

<br>
<br>
Dynamic linking is yet another crossroads of linking and memory management.
Less documented, less visible than static linking above,
but is more important in today's systems. 
<br>
<br>

This project is an education-tailered, minimal dynamic loader 
which expose the process of 
1) ELF binary parsing and understanding,
2) dependent shared library loading, and
3) indirect accesses via GOT and PLT.
<br>
<br>

Together, this project aims to get students familar with
1) memory mapped I/O on Linux,
2) mapping between symbol reference in source code and binary, and
3) `LD_PRELOAD` trick.
