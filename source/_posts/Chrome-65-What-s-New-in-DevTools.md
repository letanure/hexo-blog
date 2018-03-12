---
title: Chrome 65 - What's New in DevTools
date: 2018-03-12 11:17:47
tags:
---

## Local Overrides

[![Chrome 65 - What's New in DevTools](https://img.youtube.com/vi/D1pV7ermy6w/0.jpg)](https://www.youtube.com/watch?v=D1pV7ermy6w)

What:

Persist the changes on CSS creating a local copy of the css

How:

Sources Panel > Overrides tab > Select forlder to overrides > Choose folder > Allow

Info:

- The override files will have a purple dot on the file name
-  Will obverride the FULL file, not just the selector

Limitations:

- dont works with DOM changes (chante text or HTML)
- persist only changes on pre existent CSS classes (elemnt style add changes to the DOM)

## New accessibility tools

- Contrast ratio:
  - Show the color contrast ratio grade / recomendations
  - one checkmark is the minimum recommended contrast
  - any value below the line its ok
- Accessibilty Tab:
  - ARIA Attibutes
  . Computed properties

## New SEO and performance audits

New SEO audits on audits

## Reliable worker and async code stepping

Now the steps in breakpoints or listeners step inside the workers / Async code

The old behavior is possible with the new step button (F9)

## Multiple recordings in the Performance panel

- History of tests on Performance tab > dropdown menu with URL

## Bonus tip! Automating DevTools actions with Puppeteer

- Use [puppeteer](https://github.com/GoogleChrome/puppeteer) to manipulate chrome


Source: [Chrome 65 - What's New in DevTools](https://www.youtube.com/watch?v=D1pV7ermy6w&list=PLNYkxOF6rcIBDSojZWBv4QJNoT4GNYzQD&index=1)