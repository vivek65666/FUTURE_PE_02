# Prompt Engineering Logic

## 1. Project Overview

This project demonstrates a structured prompt engineering workflow
for creating UGC-style advertising content for a real local
business.

The objective is to create reusable prompts that generate:

- Attention-grabbing hooks
- UGC-style ad scripts
- Platform-specific content
- Conversion-focused CTAs
- Reusable advertising content

The prompts are designed to produce content suitable for
Instagram Reels, Instagram Ads, and YouTube Shorts.

---

## 2. Business Context

### Business Name

Salon Nayana

### Business Type

Hair & Beauty Salon

### Location

Brigade Road, Bengaluru, Karnataka

### Target Audience

Local customers in Bengaluru interested in hair, beauty,
styling, colour, curls, texture, and hair treatment services.

### Services

- Haircuts
- Hair Colour
- Curls & Texture
- Beauty Services
- Keratin
- Straightening
- Hair Botox

---

## 3. Problem Statement

Traditional advertising can sometimes feel overly polished
or disconnected from how people naturally communicate on social
media.

This project uses prompt engineering to create UGC-style
advertising content that is:

- Conversational
- Relatable
- Short-form friendly
- Business-specific
- Conversion-focused
- Adaptable across platforms

---

## 4. Prompt Engineering Strategy

The prompt system follows a structured framework.

### Step 1 – Define the Role

The AI is assigned a specific role such as:

- UGC advertising strategist
- Short-form content strategist
- Advertising copywriter

This establishes the expected expertise and output style.

### Step 2 – Provide Business Context

The prompts provide:

- Business name
- Business type
- Location
- Target audience
- Services

This helps reduce generic AI-generated advertising content.

### Step 3 – Define the Content Objective

Each prompt clearly defines what needs to be generated.

Examples include:

- Hooks
- UGC ad scripts
- Platform-specific scripts
- CTAs

### Step 4 – Define the Advertising Framework

The main UGC script framework is:

**Hook → Problem → Solution → Benefit → CTA**

This provides a consistent structure for conversion-focused
short-form advertising content.

### Step 5 – Define the Tone

The prompts require content that is:

- Conversational
- Natural
- Relatable
- Simple
- Authentic
- Persuasive without being aggressive

### Step 6 – Add Platform Requirements

The platform prompt adapts the same core message for:

- Instagram Reels
- Instagram Ads
- YouTube Shorts

Each platform receives different guidance for hook, pacing,
visual direction, and CTA.

### Step 7 – Add Authenticity Constraints

The prompts explicitly prevent:

- Fake testimonials
- False personal experiences
- Invented prices
- Invented discounts
- Fake urgency
- Unsupported claims
- Guaranteed results

This keeps the advertising content more responsible and
transparent.

### Step 8 – Define Output Format

Each prompt specifies exactly how the AI should structure
the response.

This makes the outputs easier to review, reuse, and organize.

---

## 5. Prompt Components

The overall framework can be represented as:

Role
+
Business Context
+
Target Audience
+
Objective
+
Advertising Framework
+
Platform Requirements
+
Tone
+
Authenticity Rules
+
Output Format
+
Quality Check

---

## 6. Prompt Modules

### Hook Prompt

Generates multiple hooks using different approaches:

- Problem
- Curiosity
- Question
- Relatable situation
- Before-you-book
- Local
- Service-specific
- Awareness
- Personal preference
- Direct attention

File:

`prompts/hook_prompt.md`

---

### UGC Script Prompt

Generates complete UGC-style advertisements using:

**Hook → Problem → Solution → Benefit → CTA**

Five different advertising angles are supported:

- Haircut / New Look
- Hair Colour
- Curls & Texture
- Hair Treatments
- General Hair & Beauty

File:

`prompts/ugc_script_prompt.md`

---

### Platform Adaptation Prompt

Adapts UGC content for:

- Instagram Reels
- Instagram Ads
- YouTube Shorts

Each platform receives specific guidance for:

- Hook
- Pacing
- Visual direction
- Spoken script
- CTA

File:

`prompts/platform_adaptation_prompt.md`

---

### CTA Prompt

Generates different CTA categories:

- Direct booking
- Service exploration
- Hair colour
- Hair treatments
- Curls & texture
- Local
- Soft CTA

File:

`prompts/cta_prompt.md`

---

## 7. Reusability

The prompt framework can be reused for other businesses.

The following variables can be changed:

- Business name
- Business type
- Location
- Target audience
- Services
- Campaign theme
- Platform

The core prompt structure can remain the same.

---

## 8. Output Quality Criteria

The generated content is evaluated using the following criteria.

### Authenticity

The content should sound natural and conversational.

### Relevance

The content should reflect the selected business and its
services.

### Conversion Intent

Each advertisement should provide a clear next step.

### Platform Fit

Content should be adapted to the platform instead of using
exactly the same script everywhere.

### Clarity

The audience should quickly understand the problem, service,
and next step.

### Accuracy

The content should avoid unsupported claims, fake testimonials,
invented offers, and fabricated experiences.

---

## 9. Tools Used

### ChatGPT

Used for prompt development, testing, refinement, and content
generation.

### GitHub

Used to organize and document prompts and generated outputs.

### Markdown

Used to maintain structured project documentation.

---

## 10. Project Workflow

The workflow used in this project is:

1. Select a real local business
2. Define the target audience
3. Identify relevant services
4. Design structured prompts
5. Generate multiple hooks
6. Generate complete UGC scripts
7. Adapt content for different platforms
8. Generate conversion-focused CTAs
9. Review outputs against quality constraints
10. Organize prompts and outputs in GitHub
11. Document the prompt engineering methodology

---

## 11. Expected Outcome

The final system provides a reusable approach for generating
UGC-style advertising content for local businesses.

The system can generate:

- Multiple hooks
- Complete UGC scripts
- Platform-specific content
- Conversion-focused CTAs

The framework can also be adapted for other businesses and
campaigns by changing the business context and campaign inputs.

---

## 12. Key Learning

This project demonstrates that effective AI advertising content
requires more than asking an AI to "write an ad."

A structured prompt provides:

- Clear business context
- Defined target audience
- Specific advertising objectives
- Consistent content frameworks
- Platform-specific requirements
- Authenticity constraints
- Clear output formatting
- Quality control criteria

This structured approach helps produce more relevant,
consistent, reusable, and practical UGC-style advertising content.
