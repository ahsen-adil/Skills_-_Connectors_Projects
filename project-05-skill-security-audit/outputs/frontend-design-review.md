# Review & Security Audit: `frontend-design` Skill

## Overview

This document provides a plain-language explanation and a security/privacy audit of the [`frontend-design`](../.claude/skills/frontend-design/SKILL.md) skill.

---

## 1. What the Skill Instructs in Plain Language

The `frontend-design` skill is an instruction set aimed at preventing generic, repetitive "AI slop" in frontend code generation. It directs the AI assistant to act like an experienced design-forward engineer when building web components, pages, or full applications.

### Key Instructions

1. **Adopt a Deliberate Aesthetic Direction**:
   - Before writing any code, identify the purpose, audience, and constraints.
   - Choose a distinct visual theme (e.g., brutalist, retro-futuristic, editorial, luxury/refined, playful, or minimalist) rather than defaulting to generic layouts.

2. **Select Characterful Typography**:
   - Avoid standard fallback fonts (e.g., Arial, Inter, Roboto).
   - Pair an expressive display font with a refined body font suited to the theme.

3. **Curate Cohesive Colors & Atmosphere**:
   - Use CSS variables for consistent palettes with strong accents.
   - Avoid generic AI design clichés (such as purple gradients on plain white backgrounds).
   - Add visual depth using subtle textures, grain overlays, gradient meshes, or layered transparencies.

4. **Incorporate Intentional Motion**:
   - Use CSS animations or libraries (such as Framer Motion for React) for micro-interactions, hover effects, and staggered reveal animations on page load.

5. **Design Unconventional Layouts**:
   - Break out of repetitive card grids using asymmetry, overlap, diagonal flow, and intentional whitespace or controlled density.

6. **Deliver Production-Grade Code**:
   - Produce fully functional, clean, and accessible code across HTML/CSS/JS, React, Vue, or the user's preferred framework.

---

## 2. Security & Privacy Audit

| Check | Result | Details |
| :--- | :--- | :--- |
| **Contacts External Servers** | **None** | Contains no URLs, endpoints, webhooks, tracking scripts, or network request logic. |
| **Handles Passwords / Credentials** | **None** | Contains no instructions, parameters, or logic for accessing, storing, or handling tokens, keys, or passwords. |
| **Data Transmission / Exfiltration** | **None** | Contains no background telemetry, file transfers, or code that could send user data externally. |

---

## 3. Verdict

**The skill is completely clean.** 

It consists purely of static Markdown guidelines focused entirely on aesthetic quality, typography, styling, and UI layout conventions.
