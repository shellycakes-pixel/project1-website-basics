---
version: alpha
name: "Project 1 M. Orengo"
description: "Change this to name your audience and describe how your design should feel to them."
omitted: [rounded]
colors:
  defaultText: "#172033"
  defaultBackground: "#FCFBFF"
  alternateText: "#3F4B63"
  alternateBackground: "#E6F1FF"
  action: "#4F6FAE"
  hover: "#354F85"
  buttonText: "#FFFFFF"
typography:
  rootSize: 16px

fontFamilies:
  body: "Lora"
  headings: "Poppins"

sizes:
  body: 1rem
  small: 0.8rem
  h1: 2.441rem
  h2: 1.953rem
  h3: 1.563rem
  h4: 1.25rem
  h5: 1rem
  h6: 0.8rem

spacing:
  sm: 0.75rem
  md: 1rem
  lg: 2rem
  xl: 3rem
  xxl: 4rem
---

## Overview

Change this to name your audience and describe how your design should feel to them.

## Colors

Default colors apply to the page. Alternate colors apply to grouped sections. Links and buttons use the action color, then hover on pointer hover. Button text uses buttonText. Keep links underlined.

- Default Text on Default Background: 15.79:1 — meets the 4.5:1 target for normal text.
- Alternate Text on Alternate Background: 7.67:1 — meets the 4.5:1 target for normal text.
- Links and buttons on Default Background: 4.83:1 — meets the 4.5:1 target for normal text.
- Links and buttons on hover on Default Background: 7.81:1 — meets the 4.5:1 target for normal text.
- Button text: 4.98:1 — meets the 4.5:1 target for normal text.
- Button text on hover: 8.05:1 — meets the 4.5:1 target for normal text.

## Typography

The base font size is 16px. Use Lora for body text and Poppins for headings. All size values use rem so changing the root size scales the full type system.

## Layout

Default line height is 1.6. Default page width is 960px. Use the spacing scale for gaps and padding: sm 0.75rem, md 1rem, lg 2rem, xl 3rem, xxl 4rem.

## Do and Don't

### Do

- Use the same exported `style.css` on every page so the type, colors, and spacing stay consistent.
- Use headings in order, beginning with one `h1`, then moving through lower heading levels as the content needs them.
- Keep underlined links and visible keyboard focus so people can find and use interactive content.

### Don't

- Create one-off colors, font sizes, or spacing values when an exported choice already fits the purpose.
- Rely on color alone to communicate meaning; use clear text, labels, or icons too.
- Change a design decision in only one file. Update the form and export a fresh set of files when the system changes.
