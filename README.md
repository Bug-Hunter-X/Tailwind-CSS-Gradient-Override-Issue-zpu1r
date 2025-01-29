# Tailwind CSS Gradient Override Issue

This repository demonstrates a common issue when using Tailwind CSS gradients: conflicts with other background classes.  The gradient may not apply as expected if other background classes are used within the same element.

## Problem

When you apply a background gradient using Tailwind's gradient utilities (like `bg-gradient-to-r`), and then add another background color class within the same element, the subsequent color class can override the gradient.

## Solution

To resolve this, ensure there are no conflicting background classes within the element using the gradient.  Alternatively, use a more specific selector or adjust the order of classes to prioritize the gradient.  If you need multiple background effects, explore using more advanced CSS techniques such as `background-image` and multiple layers.

## Setup

1. Clone this repo.
2. Run `npm install` (if necessary).
3. Open `index.html` in your browser.