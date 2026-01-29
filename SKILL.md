---
name: marketing-skills
description: Comprehensive marketing skills collection for AI agents. Use when the user needs help with conversion rate optimization (CRO), copywriting, SEO, paid advertising, email sequences, analytics tracking, pricing strategy, product launches, referral programs, A/B testing, social content, or any marketing strategy and execution tasks.
---

# Marketing Skills

A comprehensive collection of 25 specialized marketing skills for AI agents. Each skill provides expert guidance, frameworks, templates, and best practices for specific marketing domains.

## How to Use This Skill

This is a meta-skill that provides access to 25 specialized marketing skills. When a user requests marketing help, identify the most relevant skill(s) and read the corresponding `SKILL.md` file from the `skills/` directory.

## Available Skills by Category

### Conversion Rate Optimization (CRO)
- **page-cro** - Optimize conversion rates on marketing pages, landing pages, and product pages
- **signup-flow-cro** - Optimize user signup and registration flows
- **onboarding-cro** - Optimize user onboarding experiences
- **form-cro** - Optimize form design and conversion
- **popup-cro** - Optimize popup and modal conversion
- **paywall-upgrade-cro** - Optimize paywall and upgrade flows
- **ab-test-setup** - Design and implement A/B tests

### Content & Copywriting
- **copywriting** - Write persuasive marketing copy using proven frameworks
- **copy-editing** - Edit and refine marketing copy for clarity and impact
- **content-strategy** - Develop comprehensive content strategies
- **social-content** - Create engaging social media content
- **competitor-alternatives** - Create competitor alternative pages

### Email Marketing
- **email-sequence** - Design and write email sequences for various goals

### SEO & Content Scale
- **seo-audit** - Conduct comprehensive SEO audits
- **programmatic-seo** - Build programmatic SEO strategies
- **schema-markup** - Implement schema markup for better search visibility

### Paid Advertising
- **paid-ads** - Create and optimize paid advertising campaigns across platforms

### Analytics & Tracking
- **analytics-tracking** - Implement analytics tracking and event instrumentation

### Strategy & Planning
- **marketing-ideas** - Generate creative marketing ideas and campaigns
- **launch-strategy** - Plan and execute product launches
- **pricing-strategy** - Develop pricing strategies and tier structures
- **free-tool-strategy** - Design free tool strategies for lead generation
- **referral-program** - Design referral and affiliate programs
- **product-marketing-context** - Establish product marketing context for campaigns

### Foundational Knowledge
- **marketing-psychology** - Apply psychological principles to marketing

## Skill Selection Guide

When a user asks for marketing help:

1. **Identify the primary goal**: What is the user trying to achieve?
2. **Match to skill category**: Use the categories above to find relevant skills
3. **Read the specific SKILL.md**: Load `/home/ubuntu/marketingskills/skills/{skill-name}/SKILL.md`
4. **Check references**: Many skills have additional reference files in `skills/{skill-name}/references/`
5. **Combine skills when needed**: Complex projects may require multiple skills

## Tool Integrations

This repository includes integration guides for marketing tools and platforms. See `tools/REGISTRY.md` for available integrations including:

- Analytics: GA4, Mixpanel, Amplitude, PostHog, Segment
- Email: Customer.io, Mailchimp, Kit, Resend, SendGrid
- Ads: Google Ads, Meta Ads, LinkedIn Ads, TikTok Ads
- Referral: Rewardful, Tolt, Mention Me
- SEO: Ahrefs, SEMrush, Google Search Console
- E-commerce: Shopify, Stripe
- And many more...

## Examples

**User asks: "Help me improve conversions on my pricing page"**
→ Read `skills/page-cro/SKILL.md`

**User asks: "Write a welcome email sequence for new users"**
→ Read `skills/email-sequence/SKILL.md`

**User asks: "Set up analytics tracking for my app"**
→ Read `skills/analytics-tracking/SKILL.md`

**User asks: "Create a referral program"**
→ Read `skills/referral-program/SKILL.md`

**User asks: "Optimize my signup flow"**
→ Read `skills/signup-flow-cro/SKILL.md`

## Skill Structure

Each skill follows this structure:

```
skills/{skill-name}/
├── SKILL.md              # Main skill instructions
└── references/           # Optional detailed reference materials
    ├── frameworks.md
    ├── templates.md
    └── examples.md
```

## Best Practices

- **Read skills on demand**: Don't load all skills at once. Read only what's needed for the current task.
- **Check references**: Many skills have detailed reference files with frameworks, templates, and examples.
- **Combine skills**: Complex marketing projects often require multiple skills working together.
- **Use tool integrations**: Reference `tools/integrations/{tool}.md` for implementation details.

## License

MIT License - See LICENSE file for details.
