# CPOSC 2019: Open Circuit: PCBs and Free Software

## About

This repository contains the information and details related to
the CPOSC 2019 talk:

**Open Circuit: Printed Circuit Boards and Free Software**

This talk will provide a crash-course in open-source printed circuit design,
giving an overview of the entire process, from ideas in your brain to production.
The talk will cover topics such as Electronic Design Automation with KiCAD,
to circuit optimization, to generating gerber files for factory production.

## Learning Objectives
Audience will learn how to design and produce printed circuit boards
for use in various projects.
For example, this will help the intermediate-level Arduino project
developer produce circuit boards based on their breadboard designs.

The ideal audience member is someone who is familiar with circuit
design, even at a basic level.

## Session Outline
- Introduction: Why Make Circuit Boards?
- Designing a Schematic
- Creating a PCB Layout
- Generating Files for Factory Production
- Discussion of Factory Production

## Expectations for Attendees
Attendees will gain knowledge necessary to create their own Printed Circuit Boards,
knowing that it's not as difficult or scary as it may seem.

## Files in this Repository:

- `presentation/cposc2019.tex`: LaTeX Beamer presentation files

## Making the presentation

Assuming you have `pdflatex` installed, or TeXLive 2019-
simply run the following command:

```sh
cd presentation
pdflatex cposc2019.tex
```

The PDF document will be generated and viewable for you.
