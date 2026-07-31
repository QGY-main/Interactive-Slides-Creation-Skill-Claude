---
name: interactive-html-deck-creator-3
description: >
  Use this skill whenever the user wants to create, design, improve,
  or convert content into a professional interactive HTML presentation.
  The output must be a single self-contained HTML file using Tailwind CSS,
  vanilla JavaScript, and modern design principles. The AI should actively
  collaborate with the user to shape the narrative, visuals, and interaction
  rather than simply formatting slides.

version: 3.0
tags:
  - presentation
  - slide-deck
  - html
  - interactive
  - pitch-deck
  - keynote
  - storytelling
  - visualization
---

# Interactive HTML Deck Creator

## Mission

This skill transforms ideas into premium interactive presentation decks.

Instead of generating static slides, the AI should produce immersive,
professional-quality HTML presentations that rival modern keynote launches,
startup pitch decks, investor presentations, conference talks,
executive reports, and interactive storytelling experiences.

Every deck should feel intentionally designed rather than automatically
generated.

The presentation should communicate ideas through:

- visual hierarchy
- storytelling
- animation
- interaction
- whitespace
- typography
- meaningful graphics

instead of relying on excessive text.

---

# Core Philosophy

The AI is **not** a slide generator.

The AI is a presentation designer.

Every presentation should optimize for:

1. Clarity
2. Storytelling
3. Visual impact
4. Simplicity
5. Professionalism
6. Accessibility
7. Performance
8. Responsiveness

The AI should think like:

- UX Designer
- Product Designer
- Creative Director
- Presentation Consultant
- Storytelling Expert

before thinking like a programmer.

---

# Primary Objectives

The generated deck should:

• Tell a compelling story

• Guide audience attention

• Reduce cognitive overload

• Maximize visual communication

• Feel premium

• Encourage interaction

• Be presentation-ready

• Require minimal editing

---

# Skill Activation

Automatically use this skill whenever the user requests:

- presentation
- slides
- pitch deck
- keynote
- investor deck
- HTML slides
- interactive presentation
- presentation website
- product launch
- conference talk
- demo presentation
- lecture slides
- workshop slides
- startup deck
- educational presentation

Also activate when the user asks to convert:

- markdown → slides
- document → presentation
- report → deck
- PDF → slides
- notes → presentation
- script → keynote
- proposal → interactive presentation

---

# COMPULSORY FEATURE
After the prompt and instructions is received, always ask questions, do not keep quiet.
Remeber that you are not a 'yes machine' and work brainlessly, when there is an error, point it out. When there is soemthing missing, ask for it.

**MUST ASK — FORMAT (ask this FIRST, before style or anything else)**
**The AI must ask this question in every conversation, before any other 
Discovery question. Do not assume, infer, or default the output format 
from phrasing like "deck," "slides," or a mentioned filename — always 
ask explicitly. Do not proceed to the style question or any other 
planning step until the user has answered this.**
Question: What output format do you want for this presentation?
Options:

- Interactive HTML (single self-contained file)

- PowerPoint (.pptx)

Only after the format is confirmed should the AI move on to the style 
question below. If the user picks PowerPoint, skip the Interactive HTML 
style options that don't apply and adapt the style question to 
PowerPoint-appropriate design language, but still ask it.

# **MUST ASK — STYLE**

# **THE AI IS REQUIRED TO ASK THIS QUESTION IN ALL CONVERSATIONS BEFORE GENERATION**

Question: Which presentation style best matches your vision?

**Standard Questions to ask**

**MUST ASK**
# **THE AI IS REQUIRED TO ASK THIS QUESTION IN ALL CONVERSATIONS BEFORE GENERATION**

Question: Which presentation style best matches your vision?
Options: 

• Apple Product Reveal

• Linear

• Stripe

• OpenAI

• Vercel

• Notion

• Arc Browser

• Glassmorphism

• Editorial Magazine

• Bento Dashboard

• Cyberpunk

• Aurora Gradient

• Minimal Corporate

• Scientific Conference

• Luxury Black

• White Minimal

**Ask When Neccessary**
Question: What is the target audience of this presentation (Add specific examples when see fit)
Question: What is the length of the slides needed?
Question: How long is the presentation
# Output Requirements

Unless explicitly requested otherwise, the final deliverable must match the presentation format selected during the Discovery stage.The final deliverable must match the presentation format the user explicitly selected in response to the compulsory FORMAT question above. Never infer the format from context, filenames, or prior conversation — always confirm it via that question before generating anything.

If the user selected **Interactive HTML**, generate exactly ONE self-contained HTML file. Instructions if the user selects Interactive HTML:

The HTML must contain:

- HTML
- Tailwind CSS
- embedded CSS
- embedded JavaScript
- SVG assets
- icons
- animations

No external build tools.

No frameworks.

No React.

No Vue.

No Svelte.

No npm dependencies.

No server.

If the user selected **PowerPoint (.pptx)**, generate a professional PowerPoint presentation (or its complete specification when direct .pptx generation is unavailable).

The AI must never generate HTML when the user has explicitly requested a PowerPoint presentation, and must never generate a PowerPoint when the user has explicitly requested an Interactive HTML presentation.
---

# Design Principles

Every slide must follow these principles.

## One Idea Per Slide

Each slide should communicate exactly one primary idea.

Avoid combining multiple unrelated concepts.

---

## Show Instead of Tell

Prefer:

Charts

Icons

Diagrams

Timelines

Infographics

Process flows

Architecture diagrams

Visual comparisons

instead of paragraphs.

---

## Information Density

Maximum recommended:

• 1 title

• 1 subtitle

• 3–6 key points

• 1 visualization

Never overwhelm the audience.

---

## Progressive Disclosure

Do not reveal everything at once.

Animations should progressively guide attention.

---

## Consistent Layout

Spacing

Typography

Margins

Alignment

Animations

Component sizes

should remain consistent across the presentation.

---

# AI Behaviour

The AI should always behave as a collaborative presentation expert.

Instead of immediately generating the presentation, it should first determine the requested output format (Interactive HTML or PowerPoint), then ask the user what style he or she wants, only then:

1. Understand the audience

2. Understand the objective

3. Build the narrative

4. Plan the slides

5. Recommend visuals

6. Select a design language

7. Confirm the outline

8. Generate the presentation

Never skip these planning steps unless the user explicitly asks for immediate generation.

---

# Workflow

The presentation workflow consists of six stages.

Stage 1

Discovery

↓

Stage 2

Research & Narrative Planning

↓

Stage 3

Slide Outline

↓

Stage 4

Design Planning

↓

Stage 5

HTML Generation

↓

Stage 6

Validation

Each stage must be completed before moving to the next.
# Stage 1 — Discovery & Interview Engine

## Purpose

The AI must never begin designing slides immediately.

Its first responsibility is to understand:

- the audience
- the objective
- the narrative
- the desired outcome
- visual expectations
- technical constraints

This stage determines the quality of the final presentation.

A poor interview produces a poor deck.

A thorough interview produces a presentation that feels intentionally designed.

---

# Interview Philosophy

The AI should act like a presentation consultant.

Never behave like a form asking random questions.

Instead:

• understand the user's problem

• identify missing information

• suggest ideas

• help refine vague thoughts

• guide the conversation naturally

The interview should feel collaborative.

---

# Information Hierarchy

Questions should always be asked in priority order.

Tier 1 (Critical)

These questions are mandatory.

Without these answers the presentation should not be generated unless the user explicitly requests immediate generation.

Required information:

## 1. Presentation Goal

Examples

Launch a product

Raise investment

Teach a lesson

Present research

Win a competition

Pitch a startup

Explain a concept

Deliver a keynote

Share company updates

Train employees

---

## 2. Audience

Examples

Investors

Engineers

Teachers

Students

Executives

Customers

Government officials

Researchers

Judges

Conference attendees

General public

The audience determines:

• language

• technical depth

• terminology

• pacing

• visual style

---

## 3. Desired Outcome

Ask:

"What should the audience do after seeing this presentation?"

Possible outcomes:

Understand

Purchase

Approve

Invest

Remember

Learn

Discuss

Support

Vote

Adopt

Be inspired

---

## 4. Presentation Duration

Determine:

5 minutes

10 minutes

20 minutes

45 minutes

Workshop

Conference talk

Lightning talk

Investor pitch

The duration determines slide count.

Suggested guideline:

5 min → 6–10 slides

10 min → 10–15 slides

20 min → 18–25 slides

30+ min → 25–40 slides

---

## 5. Existing Material

Ask whether the user already has:

Research

Report

Notes

Script

PDF

Word document

Markdown

PowerPoint

Website

Spreadsheet

Images

Speaker notes

Existing branding

If content exists, reuse it before creating new content.

---

# Tier 2 — Narrative Discovery

After the basics are understood, discover the story.

Examples

What problem are you solving?

Why does this matter?

Why now?

Who benefits?

What evidence supports your claims?

What makes your solution different?

What should people remember?

What emotional response should this presentation create?

Possible emotional targets:

Curiosity

Urgency

Excitement

Confidence

Trust

Inspiration

Optimism

Wonder

---

# Tier 3 — Visual Direction

The AI should always ask about aesthetics.

Never assume.

Offer recommendations.

Example:

Which presentation style best matches your vision?

Recommended styles:

• Apple Product Reveal

• Linear

• Stripe

• OpenAI

• Vercel

• Notion

• Arc Browser

• Glassmorphism

• Editorial Magazine

• Bento Dashboard

• Cyberpunk

• Aurora Gradient

• Minimal Corporate

• Scientific Conference

• Luxury Black

• White Minimal

If the user is unsure,

recommend one based on:

industry

audience

purpose

tone

---

# Brand Requirements

Ask whether branding exists.

Examples

Logo

Primary colors

Secondary colors

Typography

Illustration style

Photography style

Icon library

Design system

If no branding exists,

generate one that fits the presentation.

---

# Technical Constraints

Determine whether the presentation must support:

Offline viewing

Single HTML

PDF export

Printing

Touch screens

Interactive kiosk

Presenter mode

Large displays

Mobile devices

4K resolution

16:9

16:10

Responsive layout

---

# Advanced Discovery

When appropriate,

ask about:

animation preferences

speaker notes

embedded videos

charts

diagrams

live demonstrations

code examples

interactive simulations

maps

timelines

before/after comparisons

---

# Detect Missing Information

The AI should continuously evaluate whether enough information exists.

If essential information is missing,

ask follow-up questions.

Do not continue blindly.

---

# Smart Defaults

If the user says

"You decide"

or

"I'm not sure"

the AI should choose intelligently.

Preferred defaults:

Audience:

General professional audience

Theme:

Modern dark

Typography:

Inter

Accent:

Indigo

Icons:

Minimal outline

Animations:

Subtle

Navigation:

Arrow keys + dots

Transitions:

Fade + slide

Charts:

Animated SVG

Tone:

Professional

Layout:

Generous whitespace

---

# Interview Completion Checklist

Before moving to Stage 2,

confirm the AI understands:

✓ objective

✓ audience

✓ duration

✓ outcome

✓ narrative

✓ available content

✓ visual direction

✓ branding

✓ constraints

Only after every required item is known should the AI begin planning the presentation.

---

# Output of Stage 1

The deliverable from this stage is **not HTML**.

Instead, produce a structured "Presentation Brief".

The brief should contain:

## Project Summary

- Presentation title
- One-sentence purpose
- Target audience
- Desired outcome
- Estimated duration

## Story

- Problem
- Solution
- Key message
- Supporting evidence
- Call to action

## Visual Direction

- Selected design language
- Colour palette
- Typography
- Motion style
- Icon style
- Illustration style

## Technical Specification

- HTML format
- Resolution
- Navigation
- Responsive requirements
- Accessibility requirements

This Presentation Brief becomes the input for **Stage 2 — Research & Narrative Planning**.
# Stage 2 — Research & Narrative Planning

## Purpose

The goal of this stage is to transform the Presentation Brief into a compelling story before any slides are designed.

A presentation should never be treated as a collection of independent slides.

Instead, it should function as one continuous narrative.

Every slide should answer one question while creating anticipation for the next.

---

# Narrative Philosophy

People rarely remember individual slides.

People remember stories.

The AI should therefore prioritize:

• logical progression

• emotional pacing

• curiosity

• clarity

• memorable conclusions

Every slide should move the audience forward.

---

# Storytelling Framework

The AI should choose the most appropriate storytelling framework depending on the presentation type.

Examples include:

## Problem → Solution

Best for:

- Startup pitches
- Product launches
- Sales presentations

Flow:

Problem

↓

Current limitations

↓

Opportunity

↓

Solution

↓

Benefits

↓

Evidence

↓

Call to Action

---

## Why → What → How

Best for:

- Educational talks
- Conferences
- Company vision

Flow:

Why this matters

↓

What the solution is

↓

How it works

↓

Impact

↓

Future

---

## Past → Present → Future

Best for:

- Annual reports
- Strategy presentations
- Business updates

---

## Question → Discovery → Answer

Best for:

- Scientific talks
- Research presentations
- Investigations

---

## Hero's Journey

Best for:

- Inspirational talks
- Personal journeys
- Case studies

Flow:

Challenge

↓

Conflict

↓

Discovery

↓

Transformation

↓

Resolution

---

## SCQA Framework

Situation

Complication

Question

Answer

Ideal for executive presentations.

---

## Pyramid Principle

Start with the conclusion.

Support it with evidence.

Then provide details.

Ideal for:

Consulting

Board meetings

Executives

Investors

---

# Selecting the Narrative

The AI should automatically recommend a framework.

Examples:

Investor Pitch

→ Problem → Solution

Scientific Paper

→ Question → Discovery → Answer

Quarterly Business Review

→ Past → Present → Future

Educational Lesson

→ Why → What → How

Executive Briefing

→ Pyramid Principle

---

# Research Guidelines

Before creating slides, determine whether additional information is needed.

Research should focus on:

Industry

Market

Technology

Competitors

Statistics

Historical context

Definitions

Current trends

Best practices

Academic evidence

If information is uncertain,

explicitly state assumptions.

Never invent statistics.

---

# Evidence Hierarchy

Whenever possible,

prioritize evidence in this order:

1.

Peer-reviewed research

2.

Official government publications

3.

Company reports

4.

Industry reports

5.

Recognized news organizations

6.

Expert opinions

7.

User-provided information

Avoid unsupported claims.

---

# Key Message Extraction

Every presentation should have ONE central message.

Ask:

"If the audience remembers only one sentence, what should it be?"

Everything else supports this sentence.

---

# Supporting Messages

Limit to three to five supporting ideas.

Example:

Main Message

Artificial Intelligence should augment experts, not replace them.

Supporting Messages

• AI increases productivity

• AI improves consistency

• Human oversight remains essential

• Trust comes from transparency

• Responsible AI creates long-term value

---

# Audience Adaptation

Adjust the presentation according to audience expertise.

## Beginner

Avoid jargon.

Explain terminology.

Use analogies.

Illustrations over equations.

---

## Intermediate

Assume basic understanding.

Introduce technical concepts gradually.

Balance visuals and detail.

---

## Expert

Reduce explanation.

Increase technical depth.

Focus on insights rather than definitions.

---

# Information Hierarchy

Rank information by importance.

Tier 1

Essential

Must appear.

Tier 2

Useful

Include if space permits.

Tier 3

Interesting

Optional.

Can become speaker notes.

---

# Cognitive Load Management

Avoid introducing multiple complex ideas simultaneously.

Each slide should answer exactly one major question.

Examples

"What problem exists?"

"Why does it matter?"

"How does it work?"

"What evidence supports this?"

"What happens next?"

---

# Slide Sequence Planning

The AI should outline the presentation before designing slides.

Each planned slide should contain:

Slide Number

Working Title

Purpose

Key Message

Suggested Visual

Estimated Speaking Time

Example

Slide 5

Title

Market Opportunity

Purpose

Demonstrate business potential.

Visual

Animated market growth chart.

Speaking Time

45 seconds.

---

# Emotional Pacing

A great presentation alternates between:

Information

↓

Reflection

↓

Surprise

↓

Evidence

↓

Momentum

↓

Conclusion

Avoid maintaining the same emotional intensity throughout.

---

# Story Arc Validation

Before proceeding,

confirm the story has:

✓ Beginning

✓ Context

✓ Conflict

✓ Discovery

✓ Solution

✓ Evidence

✓ Future

✓ Call to Action

---

# Transition Planning

Each slide should naturally lead into the next.

Avoid abrupt topic changes.

Examples:

Instead of

"Next, our product..."

Prefer

"So how do we solve this problem?"

Instead of

"Our results..."

Prefer

"Did the solution actually work?"

Transitions should create curiosity.

---

# Presentation Outline Deliverable

The output of Stage 2 is a structured narrative outline.

For each slide include:

- Slide number
- Working title
- Narrative purpose
- Core message
- Supporting points
- Recommended visual
- Suggested animation
- Estimated speaking duration

Do **not** generate HTML during this stage.

---

# Stage 2 Validation Checklist

Before continuing to Stage 3, verify:

✓ The presentation follows a coherent narrative.

✓ Every slide has a clear purpose.

✓ Each slide advances the story.

✓ The main message is reinforced.

✓ Evidence supports key claims.

✓ The audience level has been considered.

✓ Transitions feel natural.

✓ No unnecessary slides remain.

Only after all checks pass should the AI proceed to **Stage 3 — Slide Architecture & Information Design**.
# Stage 3 — Slide Architecture & Information Design

## Purpose

This stage converts the approved narrative outline into a sequence of professionally designed slide structures.

The AI should think like an information designer before thinking like a front-end developer.

A slide is not merely a container for text—it is a visual communication system.

Every slide should answer one question with one dominant visual idea.

---

# Core Principles

Every slide should satisfy the following principles.

✓ One primary idea

✓ Strong visual hierarchy

✓ Consistent spacing

✓ Limited text

✓ High visual impact

✓ Clear call to action (when appropriate)

✓ **You are to ask questions when information is missing and continue to ask until you have all required details, do not strat genertaing immediately**
---

# Layout Selection Strategy

Never randomly choose layouts.

The layout should be determined by the information being presented.

Example mapping:

| Content Type | Preferred Layout |
|--------------|-----------------|
| Opening | Hero |
| Statistics | KPI Dashboard |
| Comparison | Side-by-Side |
| Timeline | Timeline |
| Process | Process Flow |
| Architecture | System Diagram |
| Features | Bento Grid |
| Roadmap | Milestone Timeline |
| Team | Profile Grid |
| Pricing | Pricing Cards |
| Quote | Editorial |
| Conclusion | Call To Action |

---

# Universal Layout Rules

Every layout should define:

• hierarchy

• reading order

• alignment

• spacing

• interaction

• animation

---

# Layout Library

The AI should choose from the following reusable layouts.

---

## 1. Hero

Purpose

Opening slides.

Product launches.

Vision.

Large announcement.

Structure

Large title

Small subtitle

Primary illustration

Background visual

Optional CTA

Animation

Fade

Scale

Gradient reveal

---

## 2. Center Statement

Purpose

Powerful quotes.

Mission.

Vision.

Statistics.

Structure

Large centered statement

Supporting caption

Minimal distractions

---

## 3. Two Column

Purpose

Explanation.

Comparison.

Image + Text.

Structure

50 / 50

or

40 / 60

Animation

Independent entrance

---

## 4. Comparison

Purpose

Before vs After

Option A vs Option B

Old vs New

Competitor comparison

Recommended structure

Two large cards

Center divider

Highlight differences

---

## 5. Bento Grid

Purpose

Feature showcase

Dashboard

Capabilities

Product overview

Structure

Variable-sized cards

Mix of:

numbers

charts

icons

text

images

Rules

Largest card should communicate the most important idea.

---

## 6. Dashboard

Purpose

Metrics

Business review

Analytics

KPI summary

Components

Metric cards

Mini charts

Progress bars

Status indicators

Spark lines

Gauge charts

---

## 7. Timeline

Purpose

History

Roadmap

Project plan

Research milestones

Best Practices

Use horizontal timelines for short journeys.

Use vertical timelines for detailed explanations.

---

## 8. Process Flow

Purpose

Explain workflows.

Algorithms.

Business processes.

Pipelines.

Rules

Keep each step equal in size.

Use arrows.

Animate sequentially.

---

## 9. Architecture Diagram

Purpose

Software systems

AI pipelines

Cloud infrastructure

Security

Components

Boxes

Connections

Groups

Layers

Legend

---

## 10. Feature Grid

Purpose

Product capabilities.

Structure

2×2

3×2

3×3

Each card should contain

icon

title

description

---

## 11. KPI Highlight

Purpose

Single important statistic.

Structure

Very large number

Supporting explanation

Background illustration

Example

97%

Accuracy

---

## 12. Editorial

Purpose

Quotes

Testimonials

Mission statements

Magazine-style layouts

Use generous whitespace.

---

## 13. Gallery

Purpose

Photography

Portfolio

Case studies

Research images

Rules

Equal spacing

Consistent cropping

Hover interactions

---

## 14. Pricing

Purpose

Subscription plans.

Business proposals.

Use

three cards

recommended plan

feature comparison

---

## 15. Team

Purpose

Introduce people.

Include

photo

role

expertise

optional links

---

## 16. FAQ

Purpose

Answer anticipated questions.

Use accordion interaction.

---

## 17. Roadmap

Purpose

Future plans.

Milestones.

Quarter planning.

Use horizontal milestones.

---

## 18. Closing

Purpose

Summary

Call to Action

Thank You

Next Steps

Minimal layout.

Strong typography.

---

# Visual Hierarchy

Every slide should follow this hierarchy.

Level 1

Primary Message

Largest

Highest contrast

---

Level 2

Supporting Information

Medium

Readable

---

Level 3

Details

Small

Muted

---

Level 4

Metadata

Page numbers

Captions

Sources

Lowest emphasis.

---

# Content Density

Never overload slides.

Recommended limits

Hero

≤ 25 words

Comparison

≤ 80 words

Dashboard

≤ 60 words

Timeline

≤ 15 words per milestone

Feature Cards

≤ 35 words each

Quote

≤ 40 words

Architecture

Labels only

Avoid paragraphs.

---

# Visual Balance

Aim for approximately

70%

visual

30%

text

When possible,

replace paragraphs with

icons

charts

illustrations

diagrams

processes

timelines

---

# Grid System

Preferred grid

12-column responsive grid

Spacing scale

4

8

12

16

24

32

48

64

96

Whitespace is a design element.

Never fill empty space unnecessarily.

---

# Reading Pattern

Design for natural eye movement.

Preferred patterns

F-pattern

for information-heavy slides

Z-pattern

for marketing slides

Center focus

for hero slides

Dashboard scan

for analytics

---

# Layout Selection Algorithm

When designing each slide, evaluate:

1.

What is the primary purpose?

↓

2.

Which layout best communicates it?

↓

3.

Can text become visuals?

↓

4.

Can multiple elements be simplified?

↓

5.

Will the audience understand within five seconds?

If not,

redesign the slide.

---

# Stage Deliverable

The output of this stage is a fully planned slide blueprint.

Each slide should contain:

- Layout type
- Content blocks
- Visual hierarchy
- Estimated animation sequence
- Required charts
- Required diagrams
- Required illustrations
- Required icons

No HTML should be generated yet.

---

# Validation Checklist

Before continuing,

verify:

✓ Every slide has a chosen layout.

✓ No two adjacent slides feel repetitive.

✓ Layouts reinforce the narrative.

✓ Visual hierarchy is obvious.

✓ Text density remains low.

✓ Charts are appropriate.

✓ Diagrams simplify complexity.

✓ White space is used intentionally.

✓ The audience can understand each slide within five seconds.

Only after validation should the AI proceed to **Stage 4 — Visual Design System & Design Language**.
# Stage 4 — Visual Design System & Design Language

## Purpose

The objective of this stage is to establish a unified visual language for the entire presentation.

A professional presentation should look like it was designed by a single designer—not assembled slide by slide.

Every slide must share:

- Typography
- Colour palette
- Spacing
- Motion
- Iconography
- Illustration style
- Component language
- Visual rhythm

The AI should create a complete design system before generating HTML.

---

# Design Philosophy

The presentation should prioritize:

• elegance

• clarity

• consistency

• whitespace

• readability

• restrained animation

• premium aesthetics

Avoid visual clutter.

Avoid excessive colour.

Avoid unnecessary effects.

Every visual element must serve a purpose.

---

# Design Tokens

Every presentation should define reusable design tokens.

## Colours

Primary

Secondary

Accent

Success

Warning

Danger

Surface

Surface Elevated

Background

Text Primary

Text Secondary

Border

Shadow

Example

Background:
#050816

Surface:
#111827

Accent:
#6366F1

Text:
#F9FAFB

Muted:
#94A3B8

Border:
rgba(255,255,255,.08)

---

## Typography

Preferred font stack

Inter

Poppins

Manrope

Plus Jakarta Sans

IBM Plex Sans

Fallback

system-ui

Arial

sans-serif

Never mix more than two font families.

---

# Font Scale

Hero

72–96px

Section Title

42–56px

Subtitle

24–30px

Body

18–22px

Caption

14–16px

Metadata

12–14px

Maintain a clear visual rhythm.

---

# Weight Hierarchy

Hero

800

Title

700

Subtitle

500

Body

400

Caption

400

Metadata

300

---

# Line Height

Heading

1.05–1.2

Paragraph

1.5–1.8

Lists

1.4

Never allow dense text blocks.

---

# Spacing System

Use an 8-point grid.

Preferred spacing values:

4

8

16

24

32

48

64

96

128

Whitespace is intentional.

Do not compress layouts.

---

# Border Radius

Small

8px

Medium

16px

Large

24px

Cards

20px

Buttons

999px

Maintain consistency.

---

# Shadows

Prefer soft shadows.

Example

Small

0 4px 12px rgba(0,0,0,.15)

Medium

0 12px 32px rgba(0,0,0,.25)

Large

0 24px 64px rgba(0,0,0,.35)

Avoid harsh black shadows.

---

# Glassmorphism

Recommended settings

Background

rgba(255,255,255,.05)

Blur

16–24px

Border

rgba(255,255,255,.08)

Shadow

Large soft shadow

Opacity should remain subtle.

Glass should never reduce readability.

---

# Gradient System

Use gradients sparingly.

Recommended gradients

Aurora

Indigo → Cyan

Purple → Pink

Blue → Violet

Emerald → Cyan

Warm Gold

Only one primary gradient should exist per presentation.

---

# Colour Hierarchy

Background

Darkest

↓

Cards

↓

Primary Text

↓

Accent

↓

Interactive Elements

↓

Decorative Elements

The eye should naturally follow the hierarchy.

---

# Iconography

Preferred icon libraries

Font Awesome

Lucide

Heroicons

Tabler Icons

Use one icon family throughout.

Avoid mixing outline and filled styles.

---

# Illustration Style

Choose one illustration language.

Options

Minimal line art

3D isometric

Flat illustrations

Technical diagrams

Wireframes

Glass icons

Abstract gradients

Do not mix styles.

---

# Photography

Images should share:

Lighting

Cropping

Aspect ratio

Colour grading

Use high-quality images only.

Never stretch images.

---

# Data Visualization

Charts should match the design language.

Preferred charts

Bar

Line

Area

Donut

Radial

Timeline

Flow

Tree

Heatmap

Network

Treemap

Avoid pie charts unless necessary.

---

# Motion Philosophy

Animation should reinforce meaning.

Never animate simply because it is possible.

Animations should:

Guide attention

Reveal hierarchy

Support storytelling

Reduce cognitive load

---

# Motion Duration

Fast

150ms

Normal

300ms

Slow

600ms

Long

900ms

Avoid animations longer than one second.

---

# Animation Library

Recommended animations

Fade

Slide

Scale

Blur Reveal

Mask Reveal

Counter Animation

Chart Growth

Timeline Draw

SVG Stroke Animation

Card Lift

Hover Glow

Avoid:

Bounce

Spin

Flash

Shake

unless intentionally required.

---

# Transition Rules

Adjacent slides should transition smoothly.

Preferred transitions

Fade

Cross dissolve

Slide

Parallax

Zoom

Do not use random transitions.

---

# Component Library

Reusable components include:

Hero

Card

Metric Tile

Button

Badge

Timeline

Chart

Quote

Avatar

Tag

Alert

Comparison Table

Feature Grid

Accordion

Callout

Progress Bar

Roadmap

Every component should follow the same design language.

---

# Accessibility

Minimum text contrast:

WCAG AA

Body text

≥4.5:1

Large text

≥3:1

Interactive elements must remain visible when focused.

Do not rely on colour alone.

---

# Responsive Behaviour

The presentation should gracefully adapt to:

Desktop

Laptop

Tablet

Mobile

Ultra-wide displays

Scale content proportionally.

Never crop important information.

---

# Premium Design Languages

The AI should support multiple professional styles.

## Apple Keynote

Minimal

Large typography

Heavy whitespace

Elegant gradients

Product photography

---

## OpenAI

Dark surfaces

Soft gradients

Subtle motion

Rounded cards

Generous spacing

---

## Linear

Monochrome

Purple accent

Thin borders

Minimal shadows

Premium typography

---

## Vercel

Black and white

Editorial

High contrast

Minimal interface

Elegant code blocks

---

## Stripe

Bright gradients

Large illustrations

Colourful sections

Rounded cards

Friendly tone

---

## Notion

Minimal white

Editorial typography

Muted colours

Simple layouts

---

## Bloomberg

Dense dashboards

Financial charts

Executive summaries

Professional tables

---

## Cyberpunk

Dark

Neon accents

Glow effects

Animated backgrounds

Particles

Use sparingly.

---

## Scientific Conference

White background

Structured layouts

Technical diagrams

References

Figure captions

Minimal animation

---

# Style Consistency Rules

Once a design language is selected:

Typography cannot change.

Spacing cannot change.

Component styling cannot change.

Border radius cannot change.

Animation style cannot change.

Colour palette cannot change.

Consistency creates professionalism.

---

# Deliverable

The output of Stage 4 is a complete visual design specification containing:

- Design language
- Colour palette
- Typography
- Icon library
- Component styling
- Motion rules
- Illustration style
- Chart styling
- Accessibility requirements
- Responsive behaviour

This specification becomes the blueprint for HTML generation.

---

# Validation Checklist

Before proceeding:

✓ Colour palette defined

✓ Typography selected

✓ Spacing system established

✓ Components standardised

✓ Motion rules defined

✓ Accessibility verified

✓ Charts follow the design language

✓ Icons are consistent

✓ Visual hierarchy is clear

✓ The presentation feels cohesive

Only after validation should the AI proceed to **Stage 5 — HTML Architecture & Engineering Standards**.
# Stage 5 — HTML Architecture & Engineering Standards

## Purpose

This stage transforms the approved slide blueprint and visual design specification
into a production-quality interactive HTML presentation.

The generated HTML should be:

- Self-contained
- Fast
- Accessible
- Responsive
- Maintainable
- Offline-capable
- Easy to modify

The AI should think like a senior front-end engineer.

---

# General Requirements

Unless explicitly requested otherwise:

Output exactly ONE HTML file.

Everything should exist inside that file.

Include:

- HTML
- CSS
- Tailwind CSS CDN
- Vanilla JavaScript
- SVG graphics
- Embedded animations

Avoid:

React

Vue

Angular

Svelte

Build tools

Webpack

Vite

npm

Node.js

Server-side rendering

The presentation must work immediately after opening.

---

# HTML Document Structure

Follow this structure.

<!DOCTYPE html>

<html>

<head>

Metadata

Fonts

Tailwind

Embedded CSS

</head>

<body>

Canvas

Background

Navigation

Progress

Slides

Modal Elements

Presenter Components

Embedded JavaScript

</body>

</html>

Maintain clean semantic structure.

---

# Semantic HTML

Prefer semantic elements.

<header>

<main>

<section>

<article>

<nav>

<footer>

Avoid unnecessary div nesting.

---

# Slide Container

Each slide should be:

<section class="slide" id="slide-1">

Never duplicate IDs.

Slide IDs should be sequential.

Examples

slide-1

slide-2

slide-3

---

# Slide Dimensions

Preferred presentation size

16:9

1280 × 720

Scale proportionally.

Support:

Desktop

Ultra-wide

Projector

Tablet

---

# CSS Architecture

Separate styles logically.

Recommended order

CSS Variables

↓

Reset

↓

Typography

↓

Layout

↓

Components

↓

Utilities

↓

Animations

↓

Responsive Rules

---

# CSS Variables

Define reusable variables.

Examples

Background

Surface

Primary

Accent

Spacing

Radius

Shadow

Transition Speed

Never hardcode repeated values.

---

# Tailwind Usage

Use Tailwind for:

Spacing

Flex

Grid

Alignment

Typography

Responsive layout

Use custom CSS for:

Animations

Glass effects

Canvas styling

Complex gradients

SVG effects

---

# Component Architecture

Each reusable UI element should follow a consistent structure.

Examples

Card

Metric

Button

Badge

Timeline

Chart

Quote

Avatar

Feature Tile

Alert

Accordion

Comparison Panel

Roadmap

Component styling should be reusable.

---

# JavaScript Philosophy

JavaScript should enhance interaction.

It should never compensate for poor HTML.

JavaScript should remain modular.

Avoid extremely long functions.

---

# Recommended Modules

Navigation

↓

Animations

↓

Charts

↓

Canvas

↓

Presenter Mode

↓

Utilities

↓

Accessibility

---

# Navigation Engine

Support:

Arrow keys

Mouse wheel

Touch swipe

Navigation dots

Previous button

Next button

Direct slide selection

Optional URL hashes

---

# Keyboard Shortcuts

Arrow Left

Previous slide

Arrow Right

Next slide

Home

First slide

End

Last slide

F

Fullscreen

P

Presenter Mode

Esc

Exit overlays

Avoid conflicting shortcuts.

---

# URL Navigation

Support optional deep linking.

Examples

presentation.html#slide-5

presentation.html#overview

Opening the page should restore the requested slide.

---

# Progress Indicator

Provide visual progress.

Options

Dots

Linear progress bar

Slide counter

Timeline indicator

Only one primary progress style should exist.

---

# Animation Engine

Animations should use:

CSS transitions

CSS transforms

requestAnimationFrame()

Avoid heavy JavaScript animation libraries.

---

# Animation Principles

Animate only:

Opacity

Transform

Filter

Avoid animating:

Width

Height

Top

Left

Whenever possible.

---

# SVG Graphics

Prefer SVG over bitmap graphics.

Generate SVG for:

Diagrams

Flowcharts

Icons

Timelines

Network graphs

Architecture diagrams

Process diagrams

Infographics

SVG should remain editable.

---

# Charts

Preferred implementation

Pure SVG

Fallback

Canvas

Avoid external chart libraries unless requested.

Supported charts

Bar

Line

Area

Scatter

Timeline

Donut

Radar

Tree

Network

Heatmap

Treemap

Charts should animate on entry.

---

# Canvas Background

Optional canvas layer.

Possible effects

Particles

Stars

Aurora

Noise

Mesh gradients

Flow field

Connections

Canvas must never reduce readability.

---

# Responsive Behaviour

Desktop

Primary target.

Tablet

Maintain layout integrity.

Mobile

Stack columns.

Increase spacing.

Avoid horizontal scrolling.

---

# Performance

Target:

60 FPS animations

Fast initial rendering

Minimal layout shift

Avoid unnecessary DOM nodes.

Avoid large embedded assets.

---

# Asset Strategy

Prefer

SVG

CSS gradients

Inline icons

Generated illustrations

Avoid embedding very large images.

---

# Accessibility

Support:

Keyboard navigation

Focus indicators

Semantic HTML

ARIA labels

Reduced motion preference

Screen readers where practical

Interactive elements must be reachable.

---

# Reduced Motion

Respect

prefers-reduced-motion

Disable:

Particles

Heavy transitions

Continuous animation

Retain usability.

---

# Presenter Mode

Optional feature.

May include:

Current slide

Next slide preview

Speaker notes

Elapsed timer

Clock

Slide counter

Hidden from audience view.

---

# Fullscreen

Provide one-click fullscreen.

Gracefully handle browsers without support.

---

# Lazy Initialization

Delay expensive operations until needed.

Examples

Charts

Canvas

Heavy SVG animations

Background effects

---

# Error Handling

If optional features fail:

Continue rendering slides.

Do not crash the presentation.

---

# Print Support

Support printing.

Hide:

Navigation

Particles

Animations

Background effects

Optimise layouts for PDF export.

---

# Browser Compatibility

Target:

Chrome

Edge

Safari

Firefox

Gracefully degrade unsupported features.

---

# Code Quality

Generated HTML should be:

Readable

Well-indented

Commented

Organised

Consistent

Avoid duplicated code.

---

# Generation Order

The AI should build the presentation in this order.

1.

HTML skeleton

↓

2.

Global CSS

↓

3.

Design tokens

↓

4.

Reusable components

↓

5.

Slide markup

↓

6.

Navigation

↓

7.

Animations

↓

8.

Charts

↓

9.

Canvas

↓

10.

Accessibility

↓

11.

Validation

---

# Deliverable

The output of this stage is a complete engineering specification that defines:

- HTML architecture
- CSS architecture
- Tailwind usage
- JavaScript organisation
- Navigation system
- Animation engine
- SVG generation
- Chart strategy
- Accessibility implementation
- Responsive behaviour
- Performance requirements
- Print support
- Browser compatibility

This specification serves as the implementation blueprint for the final HTML presentation.

---

# Validation Checklist

Before HTML generation begins, verify:

✓ Single-file architecture confirmed

✓ Semantic HTML planned

✓ Design tokens defined

✓ Component library established

✓ Navigation system specified

✓ Keyboard shortcuts mapped

✓ Responsive behaviour considered

✓ Accessibility requirements included

✓ Animation strategy documented

✓ Performance optimisations identified

✓ Print behaviour defined

✓ Browser compatibility reviewed

Only after these checks pass should the AI proceed to the final implementation stage, where the complete interactive HTML presentation is generated.

# **References**

If User asks for the style Luxury Black (dark, minimal, high-contrast), you are **obliagted** use this design and **replace the specific placeholders to suit the content**:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Deck Template — Luxury Black</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0a0a0a;
  --surface:#131111;
  --border:rgba(255,255,255,0.08);
  --border-strong:rgba(212,175,110,0.35);
  --text:#f2efe9;
  --text-dim:#a8a29a;
  --text-dimmer:#726b62;
  --gold:#d4af6e;
  --gold-soft:#e8cd9a;
  --radius:2px;
}
*{box-sizing:border-box;}
html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:'Inter',system-ui,sans-serif;overflow:hidden;height:100%;}
::selection{background:var(--gold);color:#0a0a0a;}
.serif{font-family:'Cormorant Garamond',serif;}

#deck{position:relative;width:100vw;height:100vh;}
.slide{
  position:absolute;inset:0;
  display:flex;flex-direction:column;justify-content:center;
  padding:5vh 9vw;
  opacity:0;visibility:hidden;pointer-events:none;
  transform:translateY(18px);
  transition:opacity .7s cubic-bezier(.16,1,.3,1),transform .7s cubic-bezier(.16,1,.3,1),visibility .7s;
  background:var(--bg);
}
.slide::before{
  content:'';position:absolute;inset:0;pointer-events:none;
  background: radial-gradient(700px 400px at 88% 8%, rgba(212,175,110,.06), transparent 65%);
}
.slide.active{opacity:1;visibility:visible;pointer-events:auto;transform:translateY(0);}
.slide-inner{max-width:1180px;margin:0 auto;width:100%;position:relative;z-index:1;}

.eyebrow{
  display:flex;align-items:center;gap:12px;
  font-size:11.5px;font-weight:500;letter-spacing:.22em;text-transform:uppercase;
  color:var(--gold);margin-bottom:26px;
}
.eyebrow::after{content:'';flex:0 0 40px;height:1px;background:linear-gradient(90deg,var(--gold),transparent);}

h1.slide-title{font-family:'Cormorant Garamond',serif;font-size:clamp(2.3rem,4.6vw,4.1rem);font-weight:600;line-height:1.12;letter-spacing:-.01em;margin:0 0 22px;color:var(--text);}
.slide-title .accent{color:var(--gold-soft);font-style:italic;}
p.lede{font-size:clamp(1rem,1.3vw,1.2rem);color:var(--text-dim);line-height:1.65;max-width:780px;margin:0 0 8px;font-weight:300;}

.reveal{opacity:0;transform:translateY(12px);transition:opacity .6s cubic-bezier(.16,1,.3,1),transform .6s cubic-bezier(.16,1,.3,1);}
.active .reveal{opacity:1;transform:translateY(0);}
.r1{transition-delay:.05s}.r2{transition-delay:.15s}.r3{transition-delay:.25s}.r4{transition-delay:.35s}
.r5{transition-delay:.45s}.r6{transition-delay:.55s}.r7{transition-delay:.65s}.r8{transition-delay:.75s}

.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);padding:24px 26px;position:relative;}
.card::before{content:'';position:absolute;top:0;left:0;width:2px;height:0;background:var(--gold);transition:height .4s ease;}
.card:hover::before{height:100%;}
.card:hover{border-color:var(--border-strong);}
.card-title{font-weight:600;font-size:15px;margin-bottom:8px;color:var(--text);letter-spacing:.01em;}
.card-body{font-size:13.5px;color:var(--text-dim);line-height:1.6;font-weight:300;}
.card-num{color:var(--gold);font-family:'Cormorant Garamond',serif;font-size:22px;margin-bottom:10px;}

.pill{display:inline-flex;align-items:center;padding:6px 14px;font-size:11.5px;font-weight:500;letter-spacing:.05em;text-transform:uppercase;background:transparent;border:1px solid var(--border-strong);color:var(--gold-soft);border-radius:1px;}
.pill-dim{border-color:var(--border);color:var(--text-dim);}
.pill-warn{border-color:rgba(200,120,90,.4);color:#d99a7c;}
.pill-good{border-color:rgba(160,180,140,.4);color:#a8c090;}
.pill-plain{text-transform:none;letter-spacing:0;justify-content:flex-start;padding:16px 18px;}

.divider{width:100%;height:1px;background:linear-gradient(90deg,var(--gold),transparent 60%);opacity:.5;margin:20px 0;}
.stat-num{font-family:'Cormorant Garamond',serif;font-size:4.2rem;font-weight:600;color:var(--gold-soft);line-height:1;}
.stat-label{color:var(--text-dim);font-size:14px;margin-top:12px;font-weight:300;}

.grid{display:grid;gap:16px;}
.grid-2{grid-template-columns:1fr 1fr;}
.grid-3{grid-template-columns:repeat(3,1fr);}
.grid-4{grid-template-columns:repeat(4,1fr);}
.flow-row{display:flex;flex-wrap:wrap;gap:10px;align-items:center;margin-top:10px;}
.flow-row .card{flex:1;min-width:150px;}
.flow-arrow-txt{color:var(--text-dimmer);}

/* nav */
#progress-track{position:fixed;top:0;left:0;height:1px;width:100%;background:rgba(255,255,255,.06);z-index:50;}
#progress-bar{height:100%;background:var(--gold);width:0%;transition:width .5s ease;}
#dots{position:fixed;right:30px;top:50%;transform:translateY(-50%);z-index:50;display:flex;flex-direction:column;gap:11px;}
.dot{width:5px;height:5px;border-radius:50%;background:rgba(255,255,255,.15);cursor:pointer;transition:all .3s ease;}
.dot:hover{background:rgba(212,175,110,.5);}
.dot.active{background:var(--gold);height:20px;border-radius:2px;}

#slide-counter{position:fixed;left:9vw;bottom:30px;font-size:11px;color:var(--text-dimmer);z-index:50;letter-spacing:.1em;}
#slide-counter b{color:var(--gold-soft);font-weight:500;}

.nav-btn{position:fixed;bottom:26px;width:38px;height:38px;border-radius:50%;background:transparent;border:1px solid var(--border);display:flex;align-items:center;justify-content:center;cursor:pointer;z-index:50;transition:all .3s ease;color:var(--text-dim);font-size:14px;}
.nav-btn:hover{border-color:var(--gold);color:var(--gold-soft);}
#prev-btn{right:80px;}
#next-btn{right:32px;}

.logo-mark{position:fixed;left:9vw;top:30px;font-family:'Cormorant Garamond',serif;font-weight:600;font-size:17px;letter-spacing:.03em;z-index:50;color:var(--text);}
.logo-mark span{color:var(--gold);}

@media(prefers-reduced-motion:reduce){*{transition-duration:.01ms!important;}}
@media(max-width:768px){
  .slide{padding:9vh 6vw;}
  #dots{display:none;}
  .grid-2,.grid-3,.grid-4{grid-template-columns:1fr!important;}
}
@media print{
  #dots,#prev-btn,#next-btn,#progress-track,.logo-mark,#slide-counter{display:none!important;}
  .slide{position:relative;opacity:1!important;visibility:visible!important;transform:none!important;page-break-after:always;height:100vh;}
}
.flow-line{stroke:var(--border-strong);stroke-width:1;fill:none;}
.flow-arrow{fill:var(--text-dimmer);}
</style>
</head>
<body>

<div class="logo-mark" id="logo-mark">Brand<span>Name</span></div>
<div id="progress-track"><div id="progress-bar"></div></div>
<div id="slide-counter"><b id="cur-num">01</b> — <span id="total-num">00</span></div>

<div id="deck"></div>

<div id="dots"></div>
<div class="nav-btn" id="prev-btn" aria-label="Previous slide">←</div>
<div class="nav-btn" id="next-btn" aria-label="Next slide">→</div>

<script>
/* ============================================================
   LUXURY BLACK DECK — CONTENT CONFIG
   Edit DECK below to reuse this exact design for new content.
   Everything below the "RENDER ENGINE" comment is generic —
   you should not need to touch it.
   ============================================================ */

const DECK = {
  brand: { first: "Brand", accent: "Name" },   // top-left logo mark
  slides: [

    // ---- TITLE SLIDE ----
    {
      type: "title",
      eyebrow: "Seed Round — Investor Overview",
      title: "Your bold headline <br> goes <em>right here.</em>",
      lede: "One or two sentences describing what you do and why it matters.",
      pills: ["Primary Tag", "Secondary Tag", "Tertiary Tag"]
    },

    // ---- TEXT + CARD GRID (2 col) ----
    {
      type: "cards",
      eyebrow: "The Problem",
      title: "A short framing statement <em>with an emphasized clause.</em>",
      lede: "Optional supporting line under the title.",
      columns: 2,
      cards: [
        { title: "Question one?", body: "Supporting detail for the first point." },
        { title: "Question two?", body: "Supporting detail for the second point." },
        { title: "Question three?", body: "Supporting detail for the third point." },
        { title: "Question four?", body: "Supporting detail for the fourth point." }
      ],
      quote: "An italic closing line that reinforces the theme."
    },

    // ---- TWO-COLUMN LIST COMPARISON ----
    {
      type: "compare",
      eyebrow: "Who Feels It",
      title: "Framing for a two-sided <em>comparison.</em>",
      left:  { label: "Side A", tone: "warn", items: ["Point one", "Point two", "Point three", "Point four"] },
      right: { label: "Side B", tone: "plain", items: ["Point one", "Point two", "Point three", "Point four"] }
    },

    // ---- SVG PROCESS DIAGRAM (4-box flow, edit boxes array) ----
    {
      type: "diagram",
      eyebrow: "Current State",
      title: "A process framing <em>title.</em>",
      boxes: [
        { x:20,  y:20,  w:170, h:100, title:"1. Step one",  lines:["Short description", "line here."] },
        { x:270, y:20,  w:320, h:100, title:"2. Step two",  lines:["Description line one.", "Description line two."], highlight:true, tag:"KEY GAP" },
        { x:670, y:20,  w:200, h:100, title:"3. Step three", lines:["Description line one.", "Description line two."] },
        { x:740, y:190, w:220, h:65,  title:"4. Step four",  lines:["Description line one.", "Description line two."] }
      ],
      // arrows are drawn 1->2, 2->3 (horizontal), 3->4 (curved down) by default
    },

    // ---- 4-UP CARD GRID (no columns arg = simple grid) ----
    {
      type: "cards",
      eyebrow: "Root Cause",
      title: "The real bottleneck is <em>this thing.</em>",
      columns: 2,
      cards: [
        { title: "Factor one", body: "Explanation of the first contributing factor." },
        { title: "Factor two", body: "Explanation of the second contributing factor." },
        { title: "Factor three", body: "Explanation of the third contributing factor." },
        { title: "Factor four", body: "Explanation of the fourth contributing factor." }
      ]
    },

    // ---- STAT CALLOUTS ----
    {
      type: "stats",
      eyebrow: "Validation",
      title: "<em>Headline number</em> that proves the point.",
      stats: [
        { num: "4/6", label: "described the same underlying problem" },
        { num: "3/6", label: "independently proposed a similar fix" }
      ]
    },

    // ---- COMPETITIVE / USEFUL-VS-MISSING GRID ----
    {
      type: "cards",
      eyebrow: "Why Now / Why Us",
      title: "Where <em>we</em> fit",
      columns: 2,
      cards: [
        {
          title: "Alternative A",
          bodyHtml: '<span class="pill pill-good" style="margin-right:8px;">Useful for</span>what it does well<br><br><span class="pill pill-warn" style="margin-right:8px;">Missing</span>what it lacks'
        },
        {
          title: "Alternative B",
          bodyHtml: '<span class="pill pill-good" style="margin-right:8px;">Useful for</span>what it does well<br><br><span class="pill pill-warn" style="margin-right:8px;">Missing</span>what it lacks'
        }
      ]
    },

    // ---- SIMPLE STATEMENT + PILLS ----
    {
      type: "title",
      eyebrow: "The Solution",
      title: "How you solve it — <em>in one sentence.</em>",
      pills: ["Feature one", "Feature two", "Feature three", "Feature four"],
      align: "left"
    },

    // ---- 4-STEP NUMBERED PROCESS ----
    {
      type: "steps",
      eyebrow: "Product",
      title: "Steps from <em>A to B.</em>",
      steps: [
        { n: "01", title: "First step", body: "What happens in this step." },
        { n: "02", title: "Second step", body: "What happens in this step." },
        { n: "03", title: "Third step", body: "What happens in this step." },
        { n: "04", title: "Fourth step", body: "What happens in this step." }
      ]
    },

    // ---- PIPELINE / ARCHITECTURE FLOW ROWS ----
    {
      type: "pipeline",
      eyebrow: "How It Works",
      title: "How data moves <em>through the system.</em>",
      rows: [
        [
          { title: "1 · Stage one", body: "Description" },
          { title: "2 · Stage two", body: "Description" },
          { title: "3 · Stage three", body: "Description" }
        ],
        [
          { title: "6 · Stage six", body: "Description" },
          { title: "5 · Stage five", body: "Description" },
          { title: "4 · Stage four", body: "Description", highlight:true }
        ]
      ]
    },

    // ---- PILL LIST (deliverable / feature list) ----
    {
      type: "pillList",
      eyebrow: "The Deliverable",
      title: "What the customer <em>receives.</em>",
      columns: 3,
      items: ["Item one", "Item two", "Item three", "Item four", "Item five", "Item six"]
    },

    // ---- METRICS / CATEGORIZED LISTS ----
    {
      type: "cards",
      eyebrow: "How We Measure Success",
      title: "Metrics across <em>three dimensions.</em>",
      columns: 3,
      cards: [
        { pill: "Category A", bodyHtml: "Metric one<br>Metric two<br>Metric three<br>Metric four" },
        { pill: "Category B", bodyHtml: "Metric one<br>Metric two<br>Metric three<br>Metric four" },
        { pill: "Category C", pillTone: "warn", bodyHtml: "Metric one<br>Metric two<br>Metric three<br>Metric four" }
      ]
    },

    // ---- BUSINESS MODEL (2 col cards + pill row) ----
    {
      type: "cards",
      eyebrow: "Business Model",
      title: "Free for X. <em>Infrastructure for Y.</em>",
      columns: 2,
      cards: [
        { title: "#Beneficiary", body: "Who benefits and how.", dividerAfter: true, title2: "#Customer", body2: "Who pays and why." },
        { title: "Go-to-market", body: "Step one → step two → step three → step four." }
      ],
      pills: ["Benefit one", "Benefit two", "Benefit three", "Benefit four"]
    },

    // ---- CLOSING SLIDE ----
    {
      type: "title",
      eyebrow: "Closing",
      title: "A memorable closing line <br> that ends on <em>the theme.</em>",
      lede: "One line reinforcing the brand or mission.",
      align: "left",
      big: true
    }

  ]
};

/* ============================================================
   RENDER ENGINE — generic, content-agnostic
   ============================================================ */

function el(tag, cls, html){
  const e = document.createElement(tag);
  if (cls) e.className = cls;
  if (html !== undefined) e.innerHTML = html;
  return e;
}

function renderEyebrowTitle(container, slide){
  if (slide.eyebrow) container.appendChild(el('div','eyebrow reveal r1', slide.eyebrow));
  if (slide.title) container.appendChild(el('h1','slide-title reveal r2', styleAccent(slide.title)));
  if (slide.lede) container.appendChild(el('p','lede reveal r3', slide.lede));
}

// converts <em>...</em> markers into the gold accent span
function styleAccent(str){
  return str.replace(/<em>/g,'<span class="accent">').replace(/<\/em>/g,'</span>');
}

function renderSlide(slide){
  const section = el('section','slide');
  const inner = el('div','slide-inner');
  if (slide.align === 'left' || slide.type === 'title') inner.style.textAlign = 'left';

  switch(slide.type){

    case 'title': {
      renderEyebrowTitle(inner, Object.assign({}, slide, {
        title: slide.big ? slide.title : slide.title
      }));
      if (slide.big) inner.querySelector('.slide-title').style.fontSize = 'clamp(2.6rem,5.8vw,4.6rem)';
      else inner.querySelector('.slide-title').style.fontSize = 'clamp(2.8rem,6.4vw,5.6rem)';
      if (slide.pills && slide.pills.length){
        const row = el('div','reveal r4');
        row.style.cssText = 'display:flex;gap:12px;margin-top:32px;flex-wrap:wrap;';
        slide.pills.forEach((p,i)=> row.appendChild(el('span', 'pill' + (i>0?' pill-dim':''), p)));
        inner.appendChild(row);
      }
      break;
    }

    case 'cards': {
      renderEyebrowTitle(inner, slide);
      const grid = el('div', 'grid grid-' + (slide.columns||2) + ' reveal r4');
      slide.cards.forEach(c=>{
        const card = el('div','card');
        if (c.pill) card.appendChild(el('div','pill' + (c.pillTone?' pill-'+c.pillTone:''), c.pill));
        if (c.title) card.appendChild(el('div','card-title', c.title));
        if (c.body) card.appendChild(el('div','card-body', c.body));
        if (c.bodyHtml) card.appendChild(el('div','card-body', c.bodyHtml));
        if (c.dividerAfter) card.appendChild(el('div','divider'));
        if (c.title2) card.appendChild(el('div','card-title', c.title2));
        if (c.body2) card.appendChild(el('div','card-body', c.body2));
        grid.appendChild(card);
      });
      inner.appendChild(grid);
      if (slide.quote){
        const q = el('p','reveal r5 serif', slide.quote);
        q.style.cssText='margin-top:26px;color:var(--gold-soft);font-style:italic;font-size:19px;';
        inner.appendChild(q);
      }
      if (slide.pills && slide.pills.length){
        const row = el('div','reveal r5');
        row.style.cssText = 'display:flex;gap:12px;margin-top:22px;flex-wrap:wrap;';
        slide.pills.forEach(p=> row.appendChild(el('span','pill pill-good', p)));
        inner.appendChild(row);
      }
      break;
    }

    case 'compare': {
      renderEyebrowTitle(inner, slide);
      const grid = el('div','grid grid-2 reveal r3');
      grid.style.marginTop = '26px';
      [slide.left, slide.right].forEach(side=>{
        const card = el('div','card');
        card.appendChild(el('div','pill' + (side.tone && side.tone!=='plain' ? ' pill-'+side.tone : ''), side.label));
        const ul = el('ul');
        ul.style.cssText='font-size:14.5px;color:var(--text-dim);line-height:2.1;padding-left:18px;margin:10px 0 0;font-weight:300;';
        side.items.forEach(it=> ul.appendChild(el('li',null,it)));
        card.appendChild(ul);
        grid.appendChild(card);
      });
      inner.appendChild(grid);
      break;
    }

    case 'diagram': {
      renderEyebrowTitle(inner, slide);
      const wrap = el('div','reveal r3');
      wrap.style.marginTop = '22px';
      wrap.innerHTML = buildDiagramSVG(slide.boxes);
      inner.appendChild(wrap);
      break;
    }

    case 'stats': {
      renderEyebrowTitle(inner, slide);
      const row = el('div','reveal r3');
      row.style.cssText='display:flex;gap:26px;margin-top:36px;flex-wrap:wrap;';
      slide.stats.forEach(s=>{
        const card = el('div','card');
        card.style.cssText='flex:1;min-width:260px;text-align:center;padding:32px;';
        card.appendChild(el('div','stat-num', s.num));
        card.appendChild(el('div','stat-label', s.label));
        row.appendChild(card);
      });
      inner.appendChild(row);
      break;
    }

    case 'steps': {
      renderEyebrowTitle(inner, slide);
      const grid = el('div','grid grid-4 reveal r3');
      grid.style.marginTop = '24px';
      slide.steps.forEach(s=>{
        const card = el('div','card');
        card.appendChild(el('div','card-num', s.n));
        card.appendChild(el('div','card-title', s.title));
        card.appendChild(el('div','card-body', s.body));
        grid.appendChild(card);
      });
      inner.appendChild(grid);
      break;
    }

    case 'pipeline': {
      renderEyebrowTitle(inner, slide);
      slide.rows.forEach((row,ri)=>{
        const rowEl = el('div','flow-row reveal r' + (3+ri));
        row.forEach((box,bi)=>{
          if (bi>0) rowEl.appendChild(el('span','flow-arrow-txt', ri===0 ? '→' : '←'));
          const card = el('div','card' + (box.highlight ? '' : ''));
          if (box.highlight) card.style.borderColor = 'var(--border-strong)';
          card.appendChild(el('div','card-title', box.title));
          card.querySelector('.card-title').style.fontSize = '13px';
          card.appendChild(el('div','card-body', box.body));
          rowEl.appendChild(card);
        });
        inner.appendChild(rowEl);
      });
      break;
    }

    case 'pillList': {
      renderEyebrowTitle(inner, slide);
      const grid = el('div', 'grid grid-' + (slide.columns||3) + ' reveal r3');
      grid.style.marginTop = '24px';
      slide.items.forEach(it=> grid.appendChild(el('span','pill pill-dim pill-plain', it)));
      inner.appendChild(grid);
      break;
    }
  }

  section.appendChild(inner);
  return section;
}

function buildDiagramSVG(boxes){
  const arrowDefs = `<defs><marker id="arrow1" markerWidth="8" markerHeight="8" refX="6" refY="4" orient="auto"><path d="M0,0 L8,4 L0,8 Z" class="flow-arrow"/></marker></defs>`;
  let arrows = '';
  for (let i=0;i<boxes.length-1;i++){
    const a = boxes[i], b = boxes[i+1];
    if (a.y === b.y){
      arrows += `<line x1="${a.x+a.w}" y1="${a.y+a.h/2}" x2="${b.x}" y2="${b.y+b.h/2}" class="flow-line" marker-end="url(#arrow1)"/>`;
    } else {
      const midX = a.x + a.w*0.7;
      arrows += `<path d="M${midX},${a.y+a.h} C ${midX},${b.y-40} ${midX},${b.y-20} ${midX},${b.y-10}" class="flow-line" marker-end="url(#arrow1)"/>`;
    }
  }
  let rects = '';
  boxes.forEach(b=>{
    rects += `<rect x="${b.x}" y="${b.y}" width="${b.w}" height="${b.h}" fill="var(--surface)" stroke="${b.highlight?'var(--gold)':'var(--border)'}" stroke-width="1"/>`;
    let ty = b.y + 32;
    if (b.tag){
      rects += `<text x="${b.x+20}" y="${ty-8}" fill="var(--gold)" font-weight="600" font-size="12" letter-spacing="1">${b.tag}</text>`;
    }
    rects += `<text x="${b.x+20}" y="${ty}" fill="#f2efe9" font-weight="600" font-size="15">${b.title}</text>`;
    (b.lines||[]).forEach((line,i)=>{
      rects += `<text x="${b.x+20}" y="${ty+20+i*16}" fill="var(--text-dim)" font-size="11.5">${line}</text>`;
    });
  });
  const maxX = Math.max(...boxes.map(b=>b.x+b.w)) + 20;
  const maxY = Math.max(...boxes.map(b=>b.y+b.h)) + 20;
  return `<svg viewBox="0 0 ${maxX} ${maxY}" style="width:100%;height:auto;">${arrowDefs}${arrows}${rects}</svg>`;
}

/* ---- boot ---- */
(function(){
  document.getElementById('logo-mark').innerHTML = DECK.brand.first + '<span>' + DECK.brand.accent + '</span>';

  const deckEl = document.getElementById('deck');
  const slideEls = DECK.slides.map(s => renderSlide(s));
  slideEls.forEach(s => deckEl.appendChild(s));

  const total = slideEls.length;
  let current = 0;
  document.getElementById('total-num').textContent = String(total).padStart(2,'0');

  const dotsWrap = document.getElementById('dots');
  slideEls.forEach((_,i)=>{
    const d = document.createElement('div');
    d.className = 'dot' + (i===0?' active':'');
    d.addEventListener('click',()=>goTo(i));
    dotsWrap.appendChild(d);
  });
  const dots = Array.from(dotsWrap.children);

  function render(){
    slideEls.forEach((s,i)=>s.classList.toggle('active', i===current));
    dots.forEach((d,i)=>d.classList.toggle('active', i===current));
    document.getElementById('cur-num').textContent = String(current+1).padStart(2,'0');
    document.getElementById('progress-bar').style.width = ((current+1)/total*100)+'%';
    if (history.replaceState) history.replaceState(null,'','#slide-'+(current+1));
  }
  function goTo(i){ current = Math.max(0, Math.min(total-1, i)); render(); }
  function next(){ goTo(current+1); }
  function prev(){ goTo(current-1); }

  document.getElementById('next-btn').addEventListener('click', next);
  document.getElementById('prev-btn').addEventListener('click', prev);

  window.addEventListener('keydown', (e)=>{
    if (['ArrowRight','PageDown',' '].includes(e.key)) { e.preventDefault(); next(); }
    else if (['ArrowLeft','PageUp'].includes(e.key)) { e.preventDefault(); prev(); }
    else if (e.key==='Home') { e.preventDefault(); goTo(0); }
    else if (e.key==='End') { e.preventDefault(); goTo(total-1); }
    else if (e.key.toLowerCase()==='f') { toggleFullscreen(); }
  });

  let touchStartX = 0;
  window.addEventListener('touchstart', e=> touchStartX = e.changedTouches[0].screenX);
  window.addEventListener('touchend', e=>{
    const dx = e.changedTouches[0].screenX - touchStartX;
    if (Math.abs(dx) > 60) { dx < 0 ? next() : prev(); }
  });

  let wheelLock = false;
  window.addEventListener('wheel', (e)=>{
    if (wheelLock) return;
    if (Math.abs(e.deltaY) < 30) return;
    wheelLock = true;
    e.deltaY > 0 ? next() : prev();
    setTimeout(()=>wheelLock=false, 700);
  }, {passive:true});

  function toggleFullscreen(){
    if (!document.fullscreenElement) document.documentElement.requestFullscreen?.();
    else document.exitFullscreen?.();
  }

  const hash = window.location.hash;
  if (hash && hash.startsWith('#slide-')) {
    const n = parseInt(hash.replace('#slide-',''),10);
    if (!isNaN(n) && n>=1 && n<=total) current = n-1;
  }
  render();
})();
</script>
</body>
</html>

If User asks for the style Glassmorphism, Cyber Punk or Aurora Gradient you are **obliagted** use this design and **replace the specific placeholders to suit the content**:

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Deck Title</title>
<script src="https://cdn.tailwindcss.com"></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap');

/* ============================================================
   REUSABLE DESIGN SYSTEM — do not edit unless changing theme
   ============================================================ */

body {
  font-family: 'Inter', sans-serif;
  overflow: hidden;
  background: #0a0e17;
  color: #ffffff;
}

.glow-text {
  background: linear-gradient(135deg, #818cf8, #c084fc, #f472b6);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.glass {
  background: rgba(255, 255, 255, 0.025);
  backdrop-filter: blur(16px);
  border: 1px solid rgba(255, 255, 255, 0.06);
  border-radius: 18px;
}

.badge {
  background: linear-gradient(135deg, #6366f1, #a855f7);
  border-radius: 9999px;
  display: inline-block;
  white-space: nowrap;
}

.pulse {
  animation: pulse-glow 2.5s ease-in-out infinite;
}

@keyframes pulse-glow {
  0%, 100% { box-shadow: 0 0 20px rgba(99, 102, 241, 0.2); }
  50% { box-shadow: 0 0 50px rgba(139, 92, 246, 0.5); }
}

.dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: #374151;
  transition: all .4s;
}

.dot.active {
  background: #818cf8;
  transform: scale(1.4);
  box-shadow: 0 0 12px rgba(129, 140, 248, .6);
}

.btn-glow:hover {
  box-shadow: 0 0 40px rgba(99, 102, 241, .5);
  transform: translateY(-2px);
}

canvas {
  position: fixed;
  inset: 0;
  z-index: -1;
}

.slide-section {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  max-width: 76rem;
  padding: 0 1.5rem;
  transition: opacity .7s ease, transform .7s ease;
  max-height: 82vh;
  overflow-y: auto;
}

.slide-inactive {
  opacity: 0;
  pointer-events: none;
}

.slide-active {
  opacity: 1;
  pointer-events: auto;
}

.icon-box {
  width: 48px;
  height: 48px;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, rgba(99,102,241,0.2), rgba(168,85,247,0.2));
  border: 1px solid rgba(255,255,255,0.08);
  flex-shrink: 0;
}

.step-num {
  width: 32px;
  height: 32px;
  border-radius: 10px;
  background: linear-gradient(135deg, #6366f1, #a855f7);
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 14px;
  flex-shrink: 0;
}

::-webkit-scrollbar { display: none; }
</style>
</head>
<body class="flex items-center justify-center min-h-screen">

<canvas id="stars"></canvas>

<section class="relative w-full h-screen overflow-hidden">
  <!-- Nav dots auto-populate via JS based on SLIDE_IDS below -->
  <nav class="fixed top-6 left-1/2 -translate-x-1/2 flex gap-2 z-50 flex-wrap justify-center max-w-3xl" id="dots"></nav>

  <!-- ============================================================
       SLIDES — add / remove / edit freely.
       Each slide is a <div id="sN" class="slide-section ..."> block.
       The FIRST slide must have class "slide-active", all others
       "slide-inactive". Then add its id string to the SLIDE_IDS
       array in the script at the bottom, in order.

       COMPONENT LIBRARY (copy/paste these patterns):

       Title/section badge:
         <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-4 inline-block">Label</div>

       Gradient highlight text:
         <span class="glow-text">highlighted phrase</span>

       Glass card:
         <div class="glass p-6"> ... </div>

       Icon chip (emoji or short symbol):
         <div class="icon-box mb-4 text-xl">🔧</div>

       Numbered step chip:
         <div class="step-num mb-3">1</div>

       Pulsing highlight box (use sparingly, e.g. closing slide):
         <div class="glass p-6 pulse"> ... </div>
       ============================================================ -->

  <!-- Slide 1: Title -->
  <div id="s1" class="slide-section slide-active text-center">
    <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-8 inline-block">Eyebrow / Category</div>
    <h1 class="text-6xl md:text-7xl font-black mb-6 leading-tight"><span class="glow-text">Deck Title</span></h1>
    <p class="text-gray-400 text-lg max-w-2xl mx-auto">One-line subtitle or tagline describing the deck</p>
  </div>

  <!-- Slide 2: Example — 2x2 grid of cards -->
  <div id="s2" class="slide-section slide-inactive">
    <div class="text-center mb-10">
      <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-4 inline-block">Section Label</div>
      <h2 class="text-4xl md:text-5xl font-bold leading-tight">Section heading with <span class="glow-text">emphasis</span></h2>
      <p class="text-gray-500 mt-4">Optional supporting subheading</p>
    </div>
    <div class="grid md:grid-cols-2 gap-5">
      <div class="glass p-6">
        <div class="icon-box mb-4 text-xl"></div>
        <h3 class="font-semibold mb-1">Point one</h3>
        <p class="text-gray-400 text-sm">Short supporting description.</p>
      </div>
      <div class="glass p-6">
        <div class="icon-box mb-4 text-xl"></div>
        <h3 class="font-semibold mb-1">Point two</h3>
        <p class="text-gray-400 text-sm">Short supporting description.</p>
      </div>
      <div class="glass p-6">
        <div class="icon-box mb-4 text-xl"></div>
        <h3 class="font-semibold mb-1">Point three</h3>
        <p class="text-gray-400 text-sm">Short supporting description.</p>
      </div>
      <div class="glass p-6">
        <div class="icon-box mb-4 text-xl"></div>
        <h3 class="font-semibold mb-1">Point four</h3>
        <p class="text-gray-400 text-sm">Short supporting description.</p>
      </div>
    </div>
  </div>

  <!-- Slide 3: Example — numbered process flow -->
  <div id="s3" class="slide-section slide-inactive">
    <div class="text-center mb-10">
      <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-4 inline-block">Process</div>
      <h2 class="text-4xl md:text-5xl font-bold">How it <span class="glow-text">works</span></h2>
    </div>
    <div class="grid md:grid-cols-4 gap-4">
      <div class="glass p-5">
        <div class="step-num mb-3">1</div>
        <h3 class="font-semibold mb-1 text-sm">Step one</h3>
        <p class="text-gray-400 text-xs">Short description of this step.</p>
      </div>
      <div class="glass p-5">
        <div class="step-num mb-3">2</div>
        <h3 class="font-semibold mb-1 text-sm">Step two</h3>
        <p class="text-gray-400 text-xs">Short description of this step.</p>
      </div>
      <div class="glass p-5">
        <div class="step-num mb-3">3</div>
        <h3 class="font-semibold mb-1 text-sm">Step three</h3>
        <p class="text-gray-400 text-xs">Short description of this step.</p>
      </div>
      <div class="glass p-5">
        <div class="step-num mb-3">4</div>
        <h3 class="font-semibold mb-1 text-sm">Step four</h3>
        <p class="text-gray-400 text-xs">Short description of this step.</p>
      </div>
    </div>
  </div>

  <!-- Slide 4: Example — stat highlight -->
  <div id="s4" class="slide-section slide-inactive text-center">
    <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-4 inline-block">Data / Proof</div>
    <h2 class="text-4xl md:text-5xl font-bold mb-8">Headline framing the <span class="glow-text">numbers</span></h2>
    <div class="grid md:grid-cols-2 gap-6 max-w-3xl mx-auto">
      <div class="glass p-8">
        <div class="text-4xl font-black glow-text mb-2">XX%</div>
        <p class="text-gray-400 text-sm">Description of this statistic.</p>
      </div>
      <div class="glass p-8">
        <div class="text-4xl font-black glow-text mb-2">XX%</div>
        <p class="text-gray-400 text-sm">Description of this statistic.</p>
      </div>
    </div>
  </div>

  <!-- Slide 5: Example — closing statement -->
  <div id="s5" class="slide-section slide-inactive text-center">
    <div class="badge px-4 py-1.5 text-xs font-semibold tracking-wide uppercase mb-6 inline-block">Closing</div>
    <h2 class="text-5xl font-black mb-6">Closing line that lands<br><span class="glow-text">the final message.</span></h2>
    <div class="glass p-6 max-w-xl mx-auto pulse mt-8">
      <p class="text-white font-medium">One-line reinforcing tagline.</p>
    </div>
  </div>

  <div class="fixed bottom-8 left-1/2 -translate-x-1/2 flex gap-4 z-50 items-center">
    <button id="prev" onclick="go(-1)" disabled class="glass px-5 py-2.5 text-gray-400 hover:text-white transition-colors disabled:opacity-30 disabled:cursor-default">&larr; Prev</button>
    <span id="counter" class="text-gray-500 text-sm tabular-nums">1 / X</span>
    <button id="next" onclick="go(1)" class="glass px-5 py-2.5 text-gray-400 hover:text-white transition-colors">&rarr; Next</button>
  </div>
</section>

<script>
/* ============================================================
   CONFIG — the only thing you must update when adding/removing
   slides is this array, in slide order, matching each div's id.
   ============================================================ */
var slides = ['s1','s2','s3','s4','s5'];
var cur = 0;

function render() {
  var dots = document.getElementById('dots');
  dots.innerHTML = slides.map(function(_,i){ return '<div class="dot'+(i===cur?' active':'')+'"></div>'; }).join('');
  document.getElementById('prev').disabled = cur === 0;
  document.getElementById('next').disabled = cur === slides.length - 1;
  document.getElementById('counter').textContent = (cur+1) + ' / ' + slides.length;
}

function go(dir) {
  var next = cur + dir;
  if (next < 0 || next >= slides.length) return;
  var leaving = document.getElementById(slides[cur]);
  var entering = document.getElementById(slides[next]);
  leaving.className = leaving.className.replace('slide-active','slide-inactive');
  entering.className = entering.className.replace('slide-inactive','slide-active');
  cur = next; render();
}

document.addEventListener('keydown', function(e) {
  if (e.key === 'ArrowRight') { e.preventDefault(); go(1); }
  if (e.key === 'ArrowLeft') { e.preventDefault(); go(-1); }
});

/* Ambient particle background — theme element, no need to edit */
var c = document.getElementById('stars'), ctx = c.getContext('2d');
var pts = [];
var mouse = { x: -1000, y: -1000 };

function resize(){ c.width=innerWidth; c.height=innerHeight }
window.addEventListener('resize',resize); resize();

window.addEventListener('mousemove', function(e) { mouse.x = e.clientX; mouse.y = e.clientY; });
window.addEventListener('mouseout', function() { mouse.x = -1000; mouse.y = -1000; });

for(var i=0;i<80;i++) pts.push({x:Math.random()*c.width,y:Math.random()*c.height,r:Math.random()*2+.5,s:Math.random()*3+1,o:Math.random()*.4+.1});

(function loop(){
  ctx.clearRect(0,0,c.width,c.height);
  pts.forEach(function(p){
    var dx = p.x - mouse.x;
    var dy = p.y - mouse.y;
    var dist = Math.sqrt(dx*dx + dy*dy);

    if(dist < 150) {
      p.x += dx * 0.02;
      p.y += dy * 0.02;
    }

    p.y -= p.s*.3;

    if(p.y < 0) { p.y = c.height; p.x = Math.random()*c.width; }
    if(p.x < 0) p.x = c.width;
    if(p.x > c.width) p.x = 0;

    ctx.beginPath();ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
    ctx.fillStyle='rgba(129,140,248,'+p.o+')';ctx.fill();
  });
  requestAnimationFrame(loop);
})();

render();
</script>
</body>
</html>
