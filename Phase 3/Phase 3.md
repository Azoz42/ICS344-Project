# Phase 3 – Defensive Strategy Proposal

## Overview

In Phase 3, we proposed and implemented a defensive mechanism to protect the SSH service against brute-force attacks.

## Steps

- Installed and configured Fail2Ban on Metasploitable3.
- Set the SSH jail to ban IPs after 3 failed login attempts.
- Tested the defense by attempting a new brute-force attack.

## Before-and-After Results

- Before: Successful brute-force attack using Hydra.
- After: Hydra failed to complete the attack; IP address was automatically banned by Fail2Ban.

## Evidence

Screenshots in the `screenshots` folder demonstrate the success of the mitigation.

## Tools Used

- Kali Linux
- Hydra
- Splunk
- Fail2Ban
- Metasploitable3
