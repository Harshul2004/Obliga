# Obligo

### Never lose an obligation.

**Obligo** is an Email Obligation & Acknowledgement Tracking app designed for high-volume email workflows.

It answers one simple question:

> **What am I still responsible for?**

## The Problem

Reading an email doesn't mean the work created by that email is complete.

A single request can contain multiple emails, and **every new incoming email can create a new acknowledgement obligation**, even when previous emails in the same request were already handled.

## Core Model

```text
EMAIL
  ↓
OBLIGATION
  ↓
ACTION(S)
  ↓
COMPLETION
```

Obligo keeps these separate so unfinished work doesn't disappear.

## Features

* 📊 Dashboard for outstanding obligations
* ✉️ Individual email acknowledgement tracking
* ✅ Multiple actions per request
* 🔎 Universal search
* 📝 Edit requests, emails, and actions
* ⏳ Waiting state
* 🚨 Outstanding-obligation warnings
* 📜 Request timelines
* 🔐 Strict completion checks
* 🌙 End-of-shift review
* 💾 Browser-based local storage
* 📱 Responsive interface

## Example

```text
Chidi - W4 Update

Email 1 → ✓ Acknowledged
Email 2 → ✓ Acknowledged
Email 3 → ⚠ Acknowledgement Required
         → ✓ W4 Forwarded
```

The request **cannot be considered complete** while Email 3 remains unacknowledged.

## Current Status

**MVP / Prototype**

Currently runs as a standalone HTML application using browser local storage.

Future versions can add real inbox integrations, authentication, cloud storage, intelligent request detection, and automated obligation creation.

## Core Philosophy

> **Capture everything. Track every acknowledgement. Track every action. Never allow an incomplete obligation to disappear.**
