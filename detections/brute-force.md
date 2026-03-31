# Brute Force Detection

## Goal
Detect repeated failed login attempts followed by a successful login.

## Data Sources
- Windows Event Logs (Event ID 4625, 4624)
- Linux auth.log

## Detection Logic
- Multiple failed login attempts from the same IP
- Within a short time window
- Followed by a successful login

## Why It Matters
This may indicate password guessing or credential stuffing attacks.
