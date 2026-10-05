# Sanitized Product Case Study

## Context

The product was designed as a short, engaging simulation for an in-person customer experience event. Participants can come from different business roles, so the experience must feel authentic while remaining understandable without deep knowledge of a specific operational process.

## Design challenge

A realistic customer conversation includes emotion, incomplete information, time pressure and uncertainty. Adding too much process detail turns the experience into a knowledge exam; removing too much detail makes it superficial. The product therefore balances realism with a clear focus on behaviors that are broadly relevant:

- listening and discovery;
- empathy and tone;
- expectation management;
- clear explanations;
- ownership and follow-through;
- confident conversation closure.

## Experience flow

1. A participant joins the experience and selects an appropriate role context.
2. A short briefing introduces the customer and the situation.
3. The participant conducts a live voice conversation.
4. Contextual records and simple actions are available when needed.
5. The conversation ends naturally or when the allocated time expires.
6. A structured result explains strengths, improvement areas and the customer's emotional journey.
7. Event administrators can monitor participation and manage displayed results.

## Key product decisions

### Progressive disclosure

Supporting information is divided into small, quickly readable layers. Participants can stay focused on the conversation instead of reading long operational documents.

### Behavior-led scenarios

Scenarios are built around customer needs and communication choices. Operational actions support the story but do not require memorizing a specialized internal workflow.

### Natural conversation

Voice timing, turn-taking, interruptions and emotional variation are treated as product concerns rather than model defaults. The experience is calibrated to feel responsive without becoming rushed.

### Explainable evaluation

The result focuses on observable conversation behaviors. Feedback should tell the participant why an interaction worked and what could be improved, rather than showing an unexplained score.

### Event-ready operations

Participant entry, session isolation, administrator access, result visibility and failure recovery are considered part of the product experience.

## Engineering approach

The application separates scenario content, session orchestration, conversational behavior, evaluation and presentation. Environment-specific configuration and runtime records are excluded from source control. Automated checks validate release contents and essential application flows before handover.

## Outcomes and learning

The project demonstrates how conversational AI can support experiential learning when product design, domain modeling and operational readiness are developed together. The strongest improvements came from repeated end-to-end testing: simplifying the participant's decisions, shortening supporting text, improving response timing and making feedback easier to interpret.

## Disclosure boundary

This document intentionally excludes organization-specific processes, customer examples, model configuration, prompts, scoring logic, service providers, infrastructure and production metrics.

