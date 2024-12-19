# Unexpected Calculation Results with CSS calc() using Percentages and Viewport Units

This repository demonstrates an issue where the CSS `calc()` function produces unexpected results when combining percentage values and viewport units (like `vw` or `vh`).  The calculated value deviates from what's mathematically expected.

The `bug.css` file showcases the problem. The `bugSolution.css` file provides a workaround or solution if one exists.

## Bug Report

The core problem is that the order of operations or the way `calc()` handles these units seems inconsistent.  This can lead to layout and design inconsistencies, particularly in responsive design scenarios where accurate calculations are crucial.

## Solution (if available)

The `bugSolution.css` file shows the solution if one is found. This might involve alternative calculations, different unit combinations, or using JavaScript for more complex calculations.