# SOC Analysis

Write-ups from CTF and blue team training platforms, focused on
SOC analyst skills: log analysis, SIEM investigation, and detection
thinking.

Each write-up explains the **method** (what I searched, why, and how
I'd detect it in production) rather than listing room answers.

## Write-ups

| Room | Platform | Skills | Tools |
|------|----------|--------|-------|
| [Benign](writeups/tryhackme/benign/README.md) | TryHackMe | SIEM investigation, LOLBin detection, persistence hunting | Splunk |

## Repository Structure

```
writeups/      Investigation write-ups, grouped by platform
detections/    Detection ideas and queries
cheatsheets/   Quick references (Splunk SPL, Windows event IDs)
```

## Write-up Format

Every write-up follows the same structure:
summary, data source, investigation approach, key searches,
indicators, how to detect it, mitigation, MITRE ATT&CK mapping,
and lessons learned.

## About

I'm Abdulhafiz Muhammed, working towards a SOC analyst role with a longer-term
interest in purple teaming.

- GitHub: [Abdulhafiz-md](https://github.com/Abdulhafiz-md)
- LinkedIn: [Abdulhafiz Muhammed](https://www.linkedin.com/in/abdulhafiz-muhammed-b43084422)

## Note

These notes are for learning and education. Answers and flags from
training platforms are intentionally left out.
