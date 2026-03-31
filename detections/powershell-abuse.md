# PowerShell Abuse Detection

## Goal
Detect suspicious PowerShell usage.

## Indicators
- Encoded commands (-enc)
- Hidden execution (-w hidden)
- No profile usage (-nop)

## Logs
- Sysmon Event ID 1
- Windows Event ID 4688

## Detection Logic
Alert when PowerShell is executed with suspicious arguments.

## Why It Matters
Attackers often use PowerShell for fileless attacks.
