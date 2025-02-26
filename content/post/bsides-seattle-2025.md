---
date: '2025-02-26T11:07:33-08:00'
draft: false
title: 'Upcoming Talk! BSides Seattle 2025'

categories:
    - Conference Talk
tags:
    - BSides
    - Azure
    - Seattle
---

I'm super excited to be speaking at [BSides Seattle 2025](https://www.bsidesseattle.com/).

![session details](img/bsides-seattle-2025.png)

## Restless Guests

### From Subscription to Backdoor Intruder

> Discover a critical vulnerability in Azure's guest user model that enables attackers to create and control subscriptions in external tenants—without explicit privileges. This overlooked capability lets adversaries expand access, move laterally, and plant stealthy backdoors in Entra directories. With confirmed real-world attacks exploiting this gap, our first-of-its-kind research reveals how attackers leverage these pathways, why this undermines Azure's security assumptions, and what organizations must do to protect themselves before Microsoft's fixes arrive.

## Details

> Through novel research our team uncovered a critical vulnerability in Azure's guest user model, revealing that guest users can create and own subscriptions in external tenants they've joined—even without explicit privileges. This capability, which is often overlooked by Azure administrators, allows attackers to exploit these subscriptions to expand their access, move laterally within resource tenants, and create stealthy backdoor identities in the Entra directory. Alarmingly, Microsoft has confirmed real-world attacks using this method, highlighting a significant gap in many Azure threat models. This talk will share the findings from this first of its kind research into this exploit found in the wild.
>
> We'll dive into how subscriptions, intended to act as security boundaries, make it possible for any guest to create and control a subscription undermines this premise. We'll provide examples of attackers leveraging this pathway to exploit known attack vectors to escalate privileges and establish persistent access, a threat most Azure admins do not anticipate when inviting guest users. While Microsoft plans to introduce preventative options in the future, this gap leaves organizations exposed to risks they may not even realize exist––but should definitely know about!
