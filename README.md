# Unpredictable Spacing with Flexbox's 'space-between'
This repository demonstrates an uncommon issue with CSS flexbox's `space-between` property when the total width of flex items exceeds the container's width. The last item's margin might cause unpredictable spacing depending on the browser's rendering engine.

## Problem
The provided CSS uses `justify-content: space-between` to distribute items evenly within a flex container. However, when the sum of item widths surpasses the container width, the browser may not distribute the space consistently, leading to uneven spacing, particularly affecting the margin of the last item.

## Solution
The solution employs a more robust approach, adjusting the last item's margin dynamically or avoiding margin manipulation altogether, ensuring consistent spacing across different browsers and scenarios.

## Usage
1. Clone the repository.
2. Open `bug.css` to see the buggy code.
3. Open `bugSolution.css` to see the corrected code.
4. You can create a simple HTML file to test both CSS files.