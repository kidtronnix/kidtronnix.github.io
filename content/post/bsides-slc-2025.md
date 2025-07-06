---
date: '2025-02-26T11:06:57-08:00'
draft: false
title: 'Upcoming Talk! BSides SLC 2025'

categories:
    - Conference Talk
tags:
    - BSides
    - Azure
    - Salt Lake City

image = "slc.jpg"
---

I'm super excited to be speaking at [BSides SLC 2025](https://www.bsidesslc.org/).

Date: Friday, 11 Apr 2025
Time: 1:30 pm - 2:20 pm (50 minutes)

Experience Level: Intermediate-Advanced

## Restless Guests

### From Subscription to Backdoor Intruder

Through novel research our team uncovered a critical vulnerability in Azure's guest user model, revealing that guest users can create and own subscriptions in external tenants they've joined—even without explicit privileges. This capability, which is often overlooked by Azure administrators, allows attackers to exploit these subscriptions to expand their access, move laterally within resource tenants, and create stealthy backdoor identities in the Entra directory. Alarmingly, Microsoft has confirmed real-world attacks using this method, highlighting a significant gap in many Azure threat models. This talk will share the findings from this first of its kind research into this exploit found in the wild.

We'll dive into how subscriptions, intended to act as security boundaries, make it possible for any guest to create and control a subscription undermines this premise. We'll provide examples of attackers leveraging this pathway to exploit known attack vectors to escalate privileges and establish persistent access, a threat most Azure admins do not anticipate when inviting guest users. While Microsoft plans to introduce preventative options in the future, this gap leaves organizations exposed to risks they may not even realize exist––but should definitely know about!

### Details

Outline:
Introduction to the Vulnerability

- Overview of Azure's guest user model.
- The discovery: guest users can create and own subscriptions in external tenants without explicit privileges.
- Implications of the Vulnerability

Why subscriptions are assumed to act as security boundaries.
- How this capability undermines that security premise.
- Attack Techniques and Real-World Exploits

Examples of how attackers escalate privileges using these guest-controlled subscriptions.
- Real-world cases confirmed by Microsoft showcasing the severity of this exploit.
- Impact on Organizations

Risks of lateral movement and persistent access.
- Common oversights in Azure threat models related to guest users.
- Microsoft's Response and Future Preventative Options

Planned fixes and their anticipated timeline.
- Current gaps that leave organizations exposed.
- Actionable Takeaways for Defenders

Immediate steps Azure admins can take to mitigate the risk.
- Long-term strategies to strengthen tenant security against such exploits.


