



<div align="center">

# 🔮 SoulHeartMindMatch— Cognitive AI Dating Platform

<img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Deno-Deploy-000000?style=for-the-badge&logo=deno&logoColor=white"/>
<img src="https://img.shields.io/badge/Stripe-Payment_Infrastructure-635BFF?style=for-the-badge&logo=stripe&logoColor=white"/>
<img src="https://img.shields.io/badge/Framer_Motion-Animations-FF0055?style=for-the-badge&logo=framer&logoColor=white"/>

<br/>
<br/>

> **A production-grade, AI-powered dating platform engineered around multi-dimensional cognitive compatibility matching, self-learning behavioral analytics, and capital-first SaaS monetization architecture.**

<br/>

[![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-Advanced-blueviolet?style=flat-square)]()
[![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-AI--Driven-orange?style=flat-square)]()
[![System Architecture](https://img.shields.io/badge/System%20Thinking-Cognitive%20Ladder%20Design-success?style=flat-square)]()
[![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Behavioral%20ML-red?style=flat-square)]()
[![LLM Integration](https://img.shields.io/badge/LLM-Structured%20Schema%20Prompting-ff69b4?style=flat-square)]()

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Core Skill Domains](#-core-skill-domains-demonstrated)
- [AI & Prompt Engineering Architecture](#-ai--prompt-engineering-architecture)
- [Business Intelligence & Analytics](#-business-intelligence--analytics-layer)
- [Cognitive Matching Engine](#-cognitive-matching-engine)
- [Subscription & Monetization System](#-subscription--monetization-system)
- [Technical Stack & Architecture](#-technical-stack--architecture)
- [Entity Data Model](#-entity-data-model)
- [Admin & Ops Infrastructure](#-admin--operational-infrastructure)
- [ATS Keywords](#-ats-keyword-index)

---

## 🧠 About the Project

SoulHeartMindMatch is not a typical dating app.

It is a **multi-dimensional human compatibility engine** built on cognitive systems theory, self-learning behavioral data pipelines, and ethically structured constraint-based monetization.

The platform evaluates users across **100+ behavioral and psychological data points**, applies weighted scoring algorithms tuned by user-defined priorities, and continuously refines itself through a self-optimizing insight layer — all deployed on a serverless edge runtime with real-time subscriptions.

---

## 🎯 Core Skill Domains Demonstrated

---

### 🔷 Prompt Engineering

- Designed **structured JSON schema prompts** to extract typed, validated AI output from LLM calls

- Engineered **system-role context prompts** for the LLM-driven matching insight layer that produce machine-readable pattern analysis

- Built **multi-turn prompt pipelines** for user onboarding that progressively gather psychographic data across 4 sequential steps

- Implemented **response_json_schema enforcement** to guarantee structured LLM output usable directly in matching algorithms

- Designed **AI-readable entity schemas** (100+ fields) that serve as both database schema and prompt context for the cognitive engine

---

### 🔷 System Thinking & Cognitive Architecture

- Architected a **Cognitive Ladder Framework** (Levels 4–10) that maps user sophistication and algorithm maturity

- Matching insights are classified at **cognitive levels 7–10**: compression (7), creation (8), paradigm shift (9), meta-optimization (10)

- Designed a **phased infrastructure roadmap**: Phase 1 (contract layer), Phase 2 (live VPS API), Phase 3 (encrypted services + backup sync)

- All monetization triggers follow **causal constraint logic** — charges are generated only by verifiable system events, not persuasion patterns

- Built a **Capital Vault Architecture** that separates revenue flow from operational costs at the system design level

---

### 🔷 Business Intelligence with AI

- Real-time **MRR (Monthly Recurring Revenue) tracking** calculated from active subscription records

- **Customer Lifetime Value (CLV)** tracked on `CustomerIdentity` entity with immutable UUIDs across sessions

- **Behavioral fingerprinting** classifies users as: `explorer`, `selective`, `power_user`, `passive` for segmentation

- **Account health scoring**: `excellent`, `good`, `at_risk`, `churned` derived from engagement patterns

- Revenue events are categorized by trigger type (like limit exceeded, feature unlock, renewal, upgrade) enabling **funnel attribution analytics**

- **Vault routing metrics** — every dollar is tracked from payment → operational cost deduction → net vault amount

---

### 🔷 Advanced Data Analytics & ML Infrastructure

- `MatchingInsight` entity stores **feature importance weights** per successful match, enabling model retraining

- Tracks **sample size**, **confidence score**, and **success rate** per discovered pattern

- `Match.learning_data` captures: session time, profile view count, swipe speed (ms), and feature interaction sequences — all **ML-ready behavioral signals**

- Self-optimization loop: insights → applied flag → algorithm weight adjustment → new insight generation

- `derived_from_insights` array enables **DAG-style insight chaining** for compound pattern discovery

---

## 🤖 AI & Prompt Engineering Architecture

```
User Onboarding Input
        │
        ▼
┌──────────────────────────────────────┐
│   Structured JSON Schema Extraction  │  ← LLM with response_json_schema
│   (Personality, Kinks, Values, etc.) │
└──────────────────────────────────────┘
        │
        ▼
┌──────────────────────────────────────┐
│     CognitiveMatchingEngine          │  ← Multi-dimensional scorer
│     Level 7: Compression             │
│     Level 8: Creation                │
│     Level 9: Paradigm Shift          │
└──────────────────────────────────────┘
        │
        ▼
┌──────────────────────────────────────┐
│     MatchingInsight Store            │  ← Pattern confidence tracking
│     Feature Importance Weights       │
│     Auto-applied to next match cycle │
└──────────────────────────────────────┘
```

---

## 📊 Business Intelligence & Analytics Layer

| Metric | Source Entity | Calculation Method |
|--------|--------------|-------------------|
| Total Revenue | `RevenueEvent` | Sum of `amount` where `payment_status = completed` |
| MRR | `Subscription` | Active subscriptions × monthly price |
| CLV | `CustomerIdentity` | `lifetime_value` field, updated per event |
| Mutual Match Rate | `Match` | `is_mutual = true` / total matches |
| Tier Distribution | `UserProfile` | Count by `subscription_tier` |
| Vault Efficiency | `RevenueEvent` | `net_to_vault` / `amount` ratio |
| Conversion Rate | `UserProfile` + `Subscription` | Free → Paid upgrades |
| Engagement Style | `CustomerIdentity` | Behavioral classification (explorer/selective/power/passive) |

---

## 🔮 Cognitive Matching Engine

The engine scores compatibility across **5 independently weighted dimensions**:

---

**1. Kink / Intimacy Compatibility**

- Dom/Sub spectrum alignment on a -5 to +5 scale

- Stimulation intensity preference delta scoring

- Relationship style exact-match enforcement (monogamous / open / polyamorous)

---

**2. Personality Trait Compatibility**

- MBTI cross-type compatibility matrix lookup

- Energy level delta scoring (logarithmic decay at >3 point spread)

- Mood baseline alignment for long-term compatibility prediction

- Big Five trait scoring: openness, conscientiousness, agreeableness

---

**3. Geographic Proximity**

- Haversine formula distance calculation

- Score decays exponentially beyond user-configured max distance

- User-controllable `proximity_priority` weight (1–5)

---

**4. Category & Lifestyle Overlap**

- Lifestyle tags Jaccard similarity coefficient

- Love language compatibility (weighted by expression vs. reception)

- Communication style soft-matching (direct ↔ diplomatic partial credit)

- Attachment style cross-compatibility scoring

---

**5. Values Alignment**

- Ordered value priority comparison

- Earlier values weighted more heavily (priority decay function)

- Partial credit for adjacent value categories

---

## 💳 Subscription & Monetization System

---

**Free Tier**

- 10 likes per day (resets via scheduled function)

- Basic discovery feed

- No compatibility score details

---

**Premium Tier**

- Unlimited likes

- Advanced profile filters

- Full compatibility breakdown visible

- Priority message delivery

---

**Elite Tier**

- All Premium features

- Profile boost (increased discovery visibility)

- See who liked you

- Advanced analytics dashboard access

---

**Constraint-Based Monetization (BASE44 Principle)**

> Charges are triggered by verifiable system events — not dark patterns.

| Trigger | Event Type |
|---------|-----------|
| Daily like limit hit | `like_limit_exceeded` |
| Advanced filter access | `advanced_filters_unlock` |
| Profile boost request | `profile_boost_unlock` |
| Message priority request | `message_priority_unlock` |
| Monthly renewal | `monthly_renewal` |
| Annual plan upgrade | `annual_upgrade` |

---

## 🏗 Technical Stack & Architecture

---

**Frontend**

- React 18 with functional components and hooks

- TypeScript for type safety across entity interfaces

- Tailwind CSS with custom dark gradient design system

- Framer Motion for gesture-driven animations and page transitions

- React Query for server state management and cache invalidation

- React Router DOM for SPA navigation

---

**Backend / Serverless**

- Deno Deploy edge functions for all API logic

- Base44 SDK for authenticated entity operations

- Role-based access control (admin / user) enforced server-side

- Real-time entity subscriptions via WebSocket

---

**Payments**

- Stripe Checkout for session-based payment flow

- Stripe Webhooks for event-driven subscription state updates

- `STRIPE_SECRET_KEY`, `STRIPE_PUBLISHABLE_KEY`, `STRIPE_WEBHOOK_SECRET` all configured

- Async webhook signature verification (`constructEventAsync`) for Deno compatibility

---

**Data Layer**

- NoSQL entity store with JSON schema validation

- 8 core entities with relational references via ID strings

- Immutable customer UUID system for cross-session identity tracking

---

## 🗃 Entity Data Model

```
UserProfile          → Core psychographic + subscription data
Match                → Compatibility scores + ML behavioral signals
Message              → Real-time chat between mutual matches
Subscription         → Billing records with cycle and status
RevenueEvent         → Every revenue trigger with vault routing
MatchingInsight      → Self-learning pattern store
CustomerIdentity     → Immutable CLV and behavioral fingerprint
```

---

## 🔐 Admin & Operational Infrastructure

- Dual-admin system: two authorized administrator accounts

- **Setup Checklist**: Live Stripe and auth verification dashboard

- **User Management**: Override subscription tiers for any user

- **Analytics Dashboard**: Real-time KPIs — users, revenue, MRR, match rates

- **Capital Vault Dashboard**: Revenue routing metrics and event log

- **InfrastructureConnector**: Phase-based abstraction layer for scaling to encrypted VPS deployments

---

## 🏷 ATS Keyword Index

> For applicant tracking systems — relevant roles: **Prompt Engineer**, **AI Product Manager**, **Business Intelligence Analyst**, **Data Analyst (AI)**, **ML Systems Designer**, **AI Solutions Architect**, **Growth Intelligence Analyst**

---

`Prompt Engineering` `LLM Integration` `Structured Output Prompting` `JSON Schema Design`

`System Architecture` `Cognitive Systems` `AI Product Design` `Algorithm Design`

`Business Intelligence` `Revenue Analytics` `MRR Tracking` `Customer Lifetime Value`

`Behavioral Analytics` `Feature Importance` `ML Data Pipeline` `Self-Learning Systems`

`Funnel Attribution` `Conversion Optimization` `Constraint-Based Monetization`

`React` `TypeScript` `Deno` `REST APIs` `Serverless` `Edge Functions`

`Stripe Integration` `Webhook Processing` `Role-Based Access Control`

`Data Modeling` `Entity Schema Design` `NoSQL` `Real-Time Subscriptions`

`Framer Motion` `Tailwind CSS` `Component Architecture` `Responsive Design`

`SaaS Architecture` `Capital Allocation Systems` `Multi-Tenant Admin Dashboards`

---

<div align="center">

https://frequency-match-copy-75e9d2ca.base44.app/

**Built with cognitive-first system design, constraint-based monetization, and production-grade AI infrastructure.**

<br/>

*Engineered for scale. Optimized for humans.*

</div>
