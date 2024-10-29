---
author: Rob Craig
pubDatetime: 2023-01-30T15:57:52.737Z
title: SaaS - framework
postSlug: saas-template
featured: false
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - saas
  - template
  - framework
description: SaaS Base Template
---

## <a href="https://lockhartarts.co.uk/" target="_blank">SaaS Base Framework</a>

Goal is to be able to quickly spin up a fully provisioned new SaaS project.

The 'standard' SaaS functionality is available out-of-the-box.

Allows focus on what makes the app unique.

Current 'standard' functionality:

- Devise Credentials Mgmt

  - Standard sign-up & sign-in functionality
  - Email Confirmation of Sign-Up

- SendGrid (twilio interface)

  - SignUp Confirmation
  - Verified by email

- Stripe
  - Credit Card Processing
  - SignUp dependent on successful payment
