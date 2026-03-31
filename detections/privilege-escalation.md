# Privilege Escalation Detection

## Goal
Detect unauthorized privilege escalation.

## Indicators
- User added to admin group
- Use of elevated privileges
- Suspicious service creation

## Logs
- Windows Event ID 4728 / 4732
- Linux sudo logs

## Detection Logic
Alert when a user gains elevated privileges unexpectedly.

## Why It Matters
Privilege escalation allows attackers full system control.
