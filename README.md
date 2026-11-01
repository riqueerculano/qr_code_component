# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](./images/qrcode.png)

### Links

- Solution URL: [QR code component](https://riqueerculano.github.io/qr_code_component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox layout
- Mobile-first approach
- Google Fonts (`Outfit`)

### What I learned

During this challenge, I practiced structuring semantic HTML card components and styling them accurately using Flexbox to center elements both vertically and horizontally.

Here is a snippet of the layout centering technique used in CSS:

```css
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
```

### Continued development

In this project, matching the precise design spacing was trickier than expected. Fine-tuning the internal card padding (padding: 1.5rem 0.75rem) and element margins (margin-bottom: 1rem on h1) required several visual comparisons against the design preview. Additionally, integrating the Outfit font required ensuring the specific font weights were loaded cleanly to render crisp text across viewports.

In future challenges, I want to focus on:

Leveraging CSS Variables: Instead of declaring HSL values inline throughout the stylesheet, I plan to set up a dedicated :root color system to make font colors and background tones more maintainable.

Improving Fluid Typography & Spacing: I want to experiment with clamp() and scalable dynamic spacing rules so text sizes and container paddings adapt seamlessly without relying solely on fixed rem pixel breakdowns.

Exploring CSS Grid for Centering & Layouts: While Flexbox worked well for this single component, I want to practice CSS Grid techniques (such as place-content: center) on multi-card layouts.

### AI Collaboration

- Tools used: Gemini
- Usage: Generated structured documentation and reviewed layout code standards.

## Author

- Frontend Mentor - [@riqueerculano](https://www.frontendmentor.io/profile/riqueerculano)
- GitHub - [@riqueerculano](https://github.com/riqueerculano)
