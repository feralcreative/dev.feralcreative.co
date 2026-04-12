# Impartner PRM Customization: Standard vs. Orchestration Studio

## Overview

When customizing pages and forms in Impartner PRM, you have two development approaches: **Standard Customization** (HTML/CSS within Impartner's backend) and **Orchestration Studio** (Angular/TypeScript development). Understanding the difference helps you choose the right approach for your partner portal needs.

---

## Standard Customization (HTML/CSS Only)

### What It Is

Impartner's out-of-the-box platform allows you to customize pages and forms using HTML and CSS within their backend architecture. You're working within Impartner's existing framework and templates.

### Capabilities

- Custom page layouts and styling
- Branded partner portal design
- Responsive layouts for mobile/desktop
- Static content presentation
- Basic form layouts
- Custom CSS for visual consistency

### Limitations

- **No JavaScript** - Interactive components (sliders, tabs, accordions) must be built with CSS-only workarounds
- **No custom business logic** or data processing
- **No real-time validation** beyond standard form rules
- **No custom API integrations** outside Impartner's native connections
- **Fighting the platform** - Overriding Impartner's baseline CSS can be extremely difficult and time-consuming
- **Unpredictable results** - Complex CSS-only solutions may not work consistently across browsers

### The Reality

While HTML/CSS-only customization seems simpler on paper, **building interactive components without scripting is often MORE difficult and time-consuming** than using Angular. Creating CSS-only sliders, tabs, or accordions requires complex workarounds that are:

- Hard to maintain
- Difficult to guarantee will work as expected
- More time-consuming to develop than scripted solutions
- Limited in functionality compared to JavaScript-based components

### Best For

- Simple branding and visual customization
- Static content pages
- Basic forms without complex interactions
- Projects where Impartner's built-in components meet all needs
- When interactive features are NOT required

---

## Orchestration Studio (Angular Development)

### What It Is

Orchestration Studio is Impartner's advanced development module that allows you to build custom applications using **Angular and TypeScript**. This gives you full programming capabilities within the Impartner ecosystem.

### What Scripting Adds

#### **1. Custom Business Logic**

- Complex form validation rules
- Multi-step workflows and wizards
- Custom calculations and data transformations
- Conditional logic based on user roles or data

#### **2. Dynamic User Experiences**

- Real-time data updates without page refreshes
- Interactive dashboards and analytics
- Personalized content based on partner behavior
- Dynamic filtering and search capabilities

#### **3. Advanced Integrations**

- Custom API connections to external systems
- Real-time data synchronization
- Third-party service integrations
- Custom data processing pipelines

#### **4. Interactive UI Components (The Game-Changer)**

- **Sliders, tabs, accordions** - Built with JavaScript, not CSS hacks
- **Interactive configurators and tools**
- **Custom reporting interfaces**
- **Drag-and-drop functionality**
- **Advanced data visualization**
- Predictable, reliable behavior across all browsers

#### **5. State Management**

- Session-based user preferences
- Multi-page form data persistence
- Complex application state tracking
- Custom caching strategies

### Why Angular is Often Faster & More Efficient

When clients request interactive components (sliders, tabs, accordions, etc.), **Angular development is typically faster and more reliable** than trying to build them with CSS-only workarounds:

- **Clear capabilities** - You know exactly what you can build and how it will behave
- **Proven patterns** - Use established Angular components and libraries
- **Easier maintenance** - Code is more readable and maintainable
- **Guaranteed results** - No guessing if complex CSS hacks will work
- **Less time fighting the platform** - Build what you need instead of overriding Impartner's baseline styles

### Best For

- Any portal requiring interactive components (sliders, tabs, accordions, etc.)
- Partner portals requiring custom workflows
- Complex deal registration processes
- Custom reporting and analytics dashboards
- Unique business requirements not covered by standard features
- Integration-heavy implementations
- When you need predictable, reliable results

---

## Decision Guide

### Use Standard Customization When:

- Your needs align with Impartner's built-in features
- You need ONLY basic visual customization (colors, logos)
- You can work with Impartner's default fonts
- Portal requirements are purely static content
- No interactive components are needed
- Minimal custom business logic is required

### Use Orchestration Studio When:

- **You need custom fonts** (not available in standard customization)
- **You need ANY interactive components** (sliders, tabs, accordions, etc.)
- You need custom workflows or business logic
- Standard features don't meet your requirements
- You require custom integrations beyond Impartner's native options
- You need sophisticated, application-like experiences
- Real-time data processing is essential
- **You want faster, more predictable development** for complex features

---

## Cost & Complexity Comparison

| Factor                   | Standard (HTML/CSS)                                       | Orchestration Studio (Angular)          |
| ------------------------ | --------------------------------------------------------- | --------------------------------------- |
| **Development Time**     | Fast for simple styling; SLOW for interactive components  | Faster for complex/interactive features |
| **Upfront Cost**         | Lower                                                     | Higher                                  |
| **Skillset Required**    | HTML/CSS knowledge                                        | Angular/TypeScript developers           |
| **Flexibility**          | Limited to platform features                              | Highly customizable                     |
| **Maintenance**          | Minimal for static content; difficult for CSS workarounds | Easier to maintain and update           |
| **Capabilities**         | Display & basic forms only                                | Full application development            |
| **Interactive Features** | Extremely difficult, unpredictable results                | Straightforward, reliable results       |
| **Long-term Efficiency** | Higher cost when fighting platform limitations            | Lower cost for complex requirements     |

---

## The Bottom Line

**Standard HTML/CSS customization** works for simple branding and static content—but becomes MORE expensive and time-consuming when you need interactive components.

**Orchestration Studio** provides faster, more predictable development for interactive features (sliders, tabs, accordions) and complex functionality. While the upfront cost is higher, it's often more efficient than trying to build these features with CSS-only workarounds.

**The key question:** Does your portal need interactive components or custom functionality? If yes, Orchestration Studio will likely save time and money in the long run.
