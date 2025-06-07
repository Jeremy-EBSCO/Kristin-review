# Main Site Redesign

A modern Next.js-based redesign of EBSCO's main website, expanding beyond the traditional librarian audience to serve all types of users directly. This project aims to create a consumer-facing experience for accessing EBSCO's research databases and content.

## Project Overview

This is an early-stage development project building a new public-facing website for EBSCO. The goal is to expand from a librarian-only focus to one that serves all user types directly, creating multiple sales funnels for EBSCO's information products and services.

### Business Case

The redesigned website will serve as a comprehensive e-commerce platform with multiple sales funnels designed to monetize EBSCO's information assets:

1. **Direct Content Sales** - Individual articles, research papers, and reports
2. **Database Subscriptions** - Premium access to specialized research databases
3. **Institutional Access** - Enterprise solutions for libraries, schools, and organizations
4. **Freemium Conversion** - Free article previews converting to paid subscriptions
5. **Cross-selling Opportunities** - Promoting relevant databases based on user interests

### Key Features

- Dynamic topic pages for research content discovery
  - Example: `/topics/health-and-medicine/librium`
- Featured research databases with targeted recommendations
  - Current: https://www.ebsco.com/products/research-databases
- Customer spotlight sections showcasing institutional success stories
- Article access with freemium model (3 free articles, then registration required)
- Subject-based content exploration to guide users to relevant paid resources
  - Similar to: https://www.sciencedirect.com/topics/
- Personalized content recommendations to increase conversion rates

## Pages

**Homepage** - Main landing page with hero, trending topics, featured research, customer spotlight, browse by subject, featured research databases, and EBSCO solutions spotlight

**Dynamic Pages:**

- Topic Pages - `/topics/[category]/[slug]` - Overview pages for research topics
- Content Detail Pages - Individual article/tool pages powered by Research Starters, Dynamic Health, or EDS; gated behind freemium logic
- Subject Category Pages - Grid view of topics by subject
- Subject Overview Page - `/subjects` - Grid of subject areas
- Subject Group Page - `/subjects/[subject]` - Topics grouped under a subject
- Dynamic Health Detail Page - `/dynamic-health/[slug]`
- Research Record Detail Page - `/research-records/[slug]`

[View on Eraser![](https://app.eraser.io/workspace/3G94zrmlxPiZ6nErLiCP/preview?elements=lB8Csq0iWhqNV2RJJHGy7Q&type=embed)](https://app.eraser.io/workspace/3G94zrmlxPiZ6nErLiCP?elements=lB8Csq0iWhqNV2RJJHGy7Q)

## Access Model

**MVP Freemium Logic**

- Users can access 3 articles freely
- After limit: prompt registration/login
- Toggle available (e.g. debug button) for switching between logged in/out states during stakeholder review

**Future Access Features**

- IP-based institutional access detection
- Dynamic content generation based on user behavior
- Payment gateway for individual article purchase
- Full e-commerce functionality:
  - Shopping cart for multiple content types
  - Subscription management
  - Payment processing
  - License management for institutions
- Subscription management dashboard

## Content Sources

- Research Starters: https://www.ebsco.com/research-starters
- Dynamic Health: https://open.ebscomedical.com
- EBSCOhost records: https://research.ebsco.com
