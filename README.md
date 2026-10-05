# Linux Lenovo Laptop Manager

I'm trying to make a Linux app that helps manage my laptop, kinda like Lenovo Vantage.

I want to check temperatures, change performance modes, and manage battery charging from one app. I don't know how much of this will work yet, so I'll figure it out as I go.

I'll push updates here at each checkpoint so I can keep track of what I learn.

## Day 1 — The idea

Right now there's no app, just an idea and this README.

I'll start with my Lenovo laptop. If I get things working, maybe I'll add support for other laptops later.

Some things I want to try:
- Create TUI for it
- Show battery info and temperatures
- Turn battery conservation mode on or off
- Switch performance modes
- Show fan speeds
- Maybe add fan control later, once I understand how it works

## What I'll do next

First, I need to find out which settings Linux can actually read and change on my laptop.

Then I'll make a basic window that shows some real information and build from there.

## Progress

- [x] Write this README
- [ ] Check what my laptop supports on Linux
  - [ ] Note the laptop model, BIOS, distro, and kernel
  - [ ] Check battery info, temperatures, and fan readings
  - [ ] Check conservation mode and performance profiles
  - [ ] Save what works, what's missing, and what's untested
- [ ] Make the first working interface
  - [ ] Choose the language and TUI library
  - [ ] Make a basic TUI
  - [ ] Add keyboard navigation and a quit key
  - [ ] Read real laptop data
  - [ ] Show and refresh the readings
  - [ ] Handle unavailable readings
- [ ] Get one setting working
  - [ ] Pick a supported setting
  - [ ] Show its current value
  - [ ] Add a control in the TUI
  - [ ] Handle permissions and failed changes
  - [ ] Verify the change and restore the original value
- [ ] Share the first runnable version
  - [ ] Add install and run instructions
  - [ ] Add a TUI screenshot
  - [ ] List tested features and known issues

Inspired by Lenovo Vantage. Just a personal project for now.
