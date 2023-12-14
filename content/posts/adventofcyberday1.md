---
title: "[THM] Advent of Cyber 2022 Day 1"
date: 2022-12-01T14:40:10-07:00
draft: false
tags: ["cybersecurity"]
categories: ["Advent of Cyber 2022"]
---
![image](/aoc_imageheader.png)

## Day 1: Framework

The premise of today's challenge is about security framework. As we learned from the situation, Santa's website got hacked and defaced by an unknown actor. Our job is to help McSkidy (Santa's IT Admin) and her team to figure out their adversaries.

### Theory

The scenario here is about security, when things like this happened we must adhere to the company's security policies and procedures.

**Security Frameworks =** This is a documented process that defines what organizations must follow to manage their security. It also includes the steps to make following an attack.

**Cybersecurity Framework =** Developed by NIST (National Institute of Standards and Technology) that provides a detailed guide for organizations to mitigate cybersecurity risk.

> The framework focuses on five essential functions:
```
Identify -> Protect -> Detect -> Respond -> Recover
```
**ISO 27000 Series =** Developed by the International Organization of Standardization (ISO) that outline a security framework for different industries and sectors. ISO 27001 and 27002 are common for cybersecurity for creating, implementing, and managing ISMS (Information Security Management System).

**MITRE Att&CK Framework =** Developed to identify adversary plans of attack. The framework was established by known TTPs (Tactics, Techniques, Procedures). The framework was structured like a periodic table to easily map phases of the attack chain.

**Cyber Kill Chain =** Adopted by the military with the terminology "Kill Chain", it describes the structure of an attack. It consists of target identification, decision, order of the attack, and destruction of the target.

> Here are the seven stages of the Cyber Kill Chain:
![image](/cyber_kill_chain.png)

**Unified Kill Chain =** Is the unification of MITRE ATT&CK and Cyber Kill Chain frameworks. It provides a model to defend against cyber attacks from the adversary's perspective. UKC has 18 phases of attack based on TTP.

>_Cycle 1: IN_
```
1. Reconnaissance
2. Weaponisation
3. Delivery
4. Social Engineering
5. Exploitation
6. Persistence
7. Defence Evasion
8. Command Control
```
>_Cycle 2: THROUGH_
```
1. Pivoting
2. Discovery
3. Privilege Escalation
4. Execution
5. Credential Access
6. Lateral Movement
```
>_Cycle 3: OUT_
```
1. Collection
2. Exfiltration
3. Impact
4. Objectives
```
---

## Today's Challenge and Answer
Use the information we learned previously and answer the puzzle left by the adversary.

_Puzzle 1_
![image](/puzzle1.png)
_Puzzle 2_
![image](/puzzle2.png)
_Puzzle 3_
![image](/puzzle3.png)

At the end of these puzzle we will find who hacked Santa's website and the flag.

>! Spoiler Warning
![image](/day1_answer.png)




