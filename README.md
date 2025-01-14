# CSS calc() Unexpected Behavior

This repository demonstrates a bug where the `calc()` function in CSS doesn't produce the expected result when combining percentage and pixel values.  The issue is observed in certain browsers and scenarios, leading to unexpected layout.  The solution demonstrates a workaround to achieve the correct layout behavior.

## Bug Report

The `calc()` function is designed to allow dynamic calculations within CSS. However, combining percentage values with other units (such as pixels) can lead to unexpected results. The issue stems from the order of operations and how browsers interpret these mixed units.

## Solution

A workaround can be achieved using a different approach to accomplish the desired layout result, such as using `flexbox` or `grid` or adjusting the initial percentages.