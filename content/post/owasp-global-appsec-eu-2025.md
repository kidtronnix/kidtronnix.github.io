---
date: '2025-02-26T11:07:55-08:00'
draft: false
title: 'OWASP Global Appsec EU 2025'
categories:
    - Conference Talk
tags:
    - BSides
    - Azure
    - Barcelona
image: https://upload.wikimedia.org/wikipedia/commons/7/74/Sagrada_Familia_March_2015-10a.jpg
---


I'm super excited to be speaking at [OWASP Global Appsec Eu 2025](https://owasp.glueup.com/event/owasp-global-appsec-eu-2025-123983/).

## Restless Guests

### From Subscription to Backdoor Intruder

Through novel research our team uncovered a critical vulnerability in Azure's guest user model, revealing that guest users can create and own subscriptions in external tenants they've joined—even without explicit privileges. This capability, which is often overlooked by Azure administrators, allows attackers to exploit these subscriptions to expand their access, move laterally within resource tenants, and create stealthy backdoor identities in the Entra directory. Alarmingly, Microsoft has confirmed real-world attacks using this method, highlighting a significant gap in many Azure threat models. This talk will share the findings from this first of its kind research into this exploit found in the wild.

We'll dive into how subscriptions, intended to act as security boundaries, make it possible for any guest to create and control a subscription undermines this premise. We'll provide examples of attackers leveraging this pathway to exploit known attack vectors to escalate privileges and establish persistent access, a threat most Azure admins do not anticipate when inviting guest users. While Microsoft plans to introduce preventative options in the future, this gap leaves organizations exposed to risks they may not even realize exist––but should definitely know about!