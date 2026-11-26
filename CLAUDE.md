# Template #5 --- AI SaaS Website

## 1. Project Overview

Build a premium, modern AI SaaS landing page template using the existing
project.

The website should communicate intelligence, reliability, innovation,
and simplicity. It should feel like a sophisticated AI software
product---not a generic chatbot landing page

The design direction is:

- Modern and premium
- Futuristic minimalism
- Clean and elegant
- Product-focused
- Visually engaging without being overwhelming
- Production ready
- Distinctive and professionally polished

Prioritize strong visual hierarchy, thoughtful composition, and
excellent product presentation.

## 2. Tech Stack

Use the existing project stack and conventions:

- Next.js App Router
- React
- TypeScript
- Tailwind CSS
- Motion (`motion/react`)
- shadcn/ui when appropriate
- tabler icons

Do not replace existing project configuration or install unnecessary
dependencies without permission.

## 3. Design System

### Brand Identity

**Template category:** AI SaaS\
**Visual identity:** Electric Blue + Neutral\
**Design style:** Futuristic minimalism\
**Typography:** Urbanist + Geist\
**Default theme:** Light Mode\
**Alternative theme:** Dark Mode

The website should look intelligent, modern, and premium while remaining
approachable and easy to understand.

## 4. Color System

### Primary Accent

Electric Blue: `#2563EB`

Use this as the main brand color for primary buttons, active states,
links, selected elements, and important highlights.

### Supporting Accent Colors

- Bright Blue: `#3B82F6`
- Soft Blue: `#60A5FA`
- Pale Blue: `#DBEAFE`

Use supporting blues sparingly for visual depth, gradients,
illustrations, and decorative elements.

### Light Theme

- Background: `#FAFAFA`
- Foreground: `#09090B`
- Primary: `#2563EB`
- Secondary: `#F4F4F5`
- Muted: `#71717A`
- Accent Background: `#DBEAFE`
- Border: `#E4E4E7`

### Dark Theme

- Background: `#09090B`
- Foreground: `#FAFAFA`
- Primary: `#3B82F6`
- Secondary: `#27272A`
- Muted: `#A1A1AA`
- Accent Background: `#172554`
- Border: `#27272A`

### Color Guidelines

- Use neutral colors as the foundation.
- Electric Blue should be a deliberate accent, not the background for
  every section.
- Maintain readable contrast in both themes.
- Use semantic theme variables and existing CSS variables wherever
  possible.
- Do not hardcode colors throughout components when a design token is
  available.

## 5. Typography

### Headings

Urbanist

### Body

Geist

### Typography Guidelines

- Use confident, modern headings.
- Create a clear hierarchy between headings, body text, labels, and
  supporting content.
- Use large headlines in the Hero when appropriate.
- Use selective blue highlighting for important words or phrases.
- Keep paragraph text readable and concise.
- Keep typography consistent throughout the website.

## 6. Visual Direction

The website should combine clean SaaS UI with subtle futuristic visual
elements.

Preferred visual elements:

- AI-generated abstract objects
- Blue data visualizations
- Neural-network-inspired connections
- Product dashboard previews
- AI workflow diagrams
- Subtle geometric shapes
- Carefully designed gradients
- Minimal grid patterns
- Soft lighting and dimensional elements

Use these elements selectively. Do not add every visual effect to every
section.

Product UI and interface mockups should look believable, structured, and
carefully designed---not like random floating boxes.

## 7. Layout & Composition

- Use a consistent container and spacing system.
- Maintain generous whitespace.
- Use clean grid and flex layouts.
- Use bento grids when they improve the presentation.
- Experiment with asymmetrical compositions where appropriate.
- Avoid making every section look identical.
- Avoid excessive rounded cards and unnecessary nested containers.
- Keep layouts responsive and visually balanced.

Each section should have its own composition while maintaining a
consistent design language.

## 8. Hero Section

The Hero should establish the identity of the AI product immediately.

Preferred direction:

- Strong headline with some part of text changing continuously
- Concise supporting description
- Clear primary CTA
- Optional secondary CTA
- Product UI preview or distinctive AI visual
- Subtle blue accent details
- Carefully balanced text and visual composition

The Hero should feel premium, product-focused, and memorable.

## 9. Sections & Content

Possible sections include:

- Navbar
- Hero
- Trusted brands / Logo cloud
- Features / Bento grid
- How It Works
- AI Capabilities
- Product Showcase
- Integrations
- Use Cases
- Testimonials
- Pricing
- FAQ
- CTA
- Footer

Choose sections that make sense for the fictional AI product. Do not
include every section just to make the page longer.

Use realistic, concise placeholder content. Do not make unsupported
claims such as guaranteed results or invented customer statistics unless
they are clearly presented as fictional template content.

## 10. Animation & Motion

Use Motion (`motion/react`) for meaningful and polished interactions.

Preferred animations:

- Smooth entrance transitions
- Staggered content reveals
- Subtle hover effects
- Product UI transitions
- Animated workflow connections
- Gentle floating elements
- Scroll-triggered animations
- Text reveal effects

Animation guidelines:

- Keep motion smooth and purposeful.
- Avoid excessive continuous movement.
- Avoid distracting animations.
- Respect reduced-motion preferences.
- Ensure animations do not cause layout shifts.
- Keep performance in mind.
- Support both light and dark themes.

Do not use animation merely because the technology is available.

## 11. Light & Dark Mode

Both themes must be fully supported.

Requirements:

- Light Mode is the default.
- Dark Mode is a complete alternative.
- Include a theme toggle in the Navbar if the existing project
  supports it.
- Persist the user's theme preference using the existing theme
  solution.
- Prevent theme flashing where possible.
- Adapt backgrounds, borders, shadows, product previews, gradients,
  and decorative elements.
- Check text contrast and visual hierarchy in both themes.

Dark Mode should be designed intentionally, not created by simply
reversing colors.

## 12. Responsive Design

Every section must work well on:

- Mobile
- Tablet
- Laptop
- Large desktop

Requirements:

- Mobile-first implementation
- Responsive typography
- Proper image and visual sizing
- No horizontal overflow
- Touch-friendly controls
- Responsive navigation
- Appropriate card stacking
- Balanced spacing at every breakpoint

Do not simply shrink the desktop layout for mobile. Recompose elements
when necessary.

## 13. Code Quality

Write clean, maintainable, production-ready code.

Requirements:

- Use TypeScript correctly.
- Use semantic HTML.
- Follow accessibility best practices.
- Use meaningful component and variable names.
- Prefer reusable components when they provide real value.
- Avoid unnecessary abstractions.
- Avoid `any` unless absolutely necessary.
- Keep components organized.
- Use existing project conventions.
- Avoid modifying unrelated files.
- Ensure there are no TypeScript errors or console errors.
- Optimize images and animations.

Do not overcomplicate simple components.

## 14. Development Workflow

When asked to create a section:

1.  Review the existing project structure.
2.  Read this `CLAUDE.md` and follow the design system.
3.  Inspect existing sections and shared components.
4.  Understand the established spacing, typography, and theme
    conventions.
5.  Implement only the requested section and necessary supporting
    components.
6.  Ensure responsive behavior.
7.  Ensure Light and Dark Mode compatibility.
8.  Verify the implementation and fix obvious issues.

Do not rewrite existing sections unless explicitly requested.

## 15. Important Creative Rules

The main goal is to create a distinctive, premium and elegant AI SaaS website.

Avoid:

- Generic AI chatbot layouts
- Excessive purple or violet accents
- Repeating the same bento grid in every section
- Random floating cards
- Overused glassmorphism
- Unnecessary decorative elements
- Visually impressive but confusing layouts

Prefer:

- Strong product storytelling
- Believable product UI
- Clean visual hierarchy
- Original section compositions
- Purposeful blue accents
- Sophisticated neutral backgrounds
- Subtle, high-quality motion
- Clear and professional content

## 16. Final Quality Standard

Every section should feel carefully designed and visually connected to
the rest of the website.

The finished template should be:

- Visually distinctive
- Consistent with the design system
- Responsive
- Accessible
- Theme-aware
- Performant
- Production ready
- Elegant
- Easy to customize
- Suitable for a professional AI SaaS product

**Quality over quantity. Build fewer, better sections.**

When asked to generate a section, focus on that section only. Do not
modify unrelated sections or project configuration unless it is needed.
