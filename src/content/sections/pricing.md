---
# Choose A Plan
title: "Choose A Plan"
subtitle: "Created to Simplify Your Experience and Unlock the Advantages of Draftify's Innovative Technologies"


plans:
  monthly:
    - plan: "Basic"
      audience: "For solo entrepreneurs"
      users: "per month"
      price_prefix: "$"
      price: "399"
      features: &START_FEATURES
        - "Template Creation"
        - "AI Agent Responsivity"
        - "AI Research Cross-Checking"
        - "Email Support"
      button:
        enable: true
        label: "Select Plan"
        link: "/contact/"
    - plan: "Premium"
      audience: "For small teams"
      users: "per person, per month"
      price_prefix: "$"
      price: "799"
      features:  &PREMIUM_FEATURES
        - "Everything in Basic"
        - "Priority Email Support"
      button:
        enable: true
        label: "Select Plan"
        link: "/contact/"
  yearly:
    - plan: "Basic"
      audience: "For solo entrepreneurs"
      users: "per year"
      price_prefix: "$"
      price: "3990"
      features:
        *START_FEATURES
      button:
        enable: true
        label: "Select Basic Plan"
        link: "/contact/"
    - plan: "Premium"
      audience: "For small teams"
      users: "per year"
      price_prefix: "$"
      price: "7990"
      features: *PREMIUM_FEATURES
      button:
        enable: true
        label: "Select Plan"
        link: "/contact/"
---
