# Unexpected Horizontal Scrollbars in CSS

This repository demonstrates a common CSS issue where setting `width: 100%` and `box-sizing: border-box` on a div unexpectedly results in horizontal scrollbars.  The issue arises because `box-sizing: border-box` includes padding and borders in the element's total width, potentially exceeding the parent container's width.  The solution involves carefully considering content width or using techniques like `overflow-x: hidden` (with caution).