# FlowVision Coding Standards

Version: 1.0

---

# Purpose

This document defines the engineering standards used throughout the FlowVision project.

Every contributor should follow these rules to ensure consistency, readability, and maintainability.

---

# Engineering Philosophy

Code is written for humans first.

Readable code is more valuable than clever code.

Consistency is more important than personal preference.

---

# Naming Conventions

## Files

Use lowercase with hyphens.

Example:

device-service.ts

topology-engine.ts

network-health.ts

---

## Folders

Use lowercase.

Example:

components

services

hooks

pages

assets

---

## Variables

Use camelCase.

Good:

deviceStatus

interfaceSpeed

networkHealth

Bad:

Device_Status

DEVICESTATUS

device_status

---

## Components

Use PascalCase.

Example:

Dashboard

DeviceCard

TopologyCanvas

AlertPanel

---

## Functions

Use camelCase.

Function names should describe an action.

Good:

calculateBandwidth()

loadDevices()

updateTopology()

Bad:

data()

test()

value()

---

# API Routes

Use nouns instead of verbs.

Good

/api/devices

/api/interfaces

/api/alerts

/api/topology

Avoid

/getDevices

/loadAlerts

/updateDevice

---

# Comments

Write comments only when necessary.

Code should explain itself whenever possible.

---

# Logging

Every error must be logged.

Never ignore exceptions.

Log levels:

INFO

WARNING

ERROR

CRITICAL

---

# Error Handling

Never expose internal errors to users.

Show friendly messages.

Log technical details internally.

---

# UI Rules

Never overload the screen.

Always prioritize readability.

Use whitespace generously.

Consistency is mandatory.

---

# Git Commits

Use conventional commit messages.

Examples:

docs: update dashboard specification

feat: add topology component

fix: resolve login issue

refactor: simplify device service

style: improve sidebar spacing

---

# Branch Strategy

main

Always stable.

feature/*

For new features.

fix/*

For bug fixes.

---

# Final Principle

Every line of code should make FlowVision easier to understand, easier to maintain, and easier to extend.
