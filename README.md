# React Native FlatList Performance Issue

This repository demonstrates a performance issue encountered when using FlatList in React Native with a large dataset.  The application becomes sluggish and unresponsive when rendering thousands of items. This example uses 10,000 items to highlight the problem.

## Problem

Rendering a large number of items in a FlatList can cause significant performance issues in React Native.  The default behavior of FlatList is to render all items at once, resulting in a significant performance hit.  The UI thread gets blocked and leads to slowness and potential crashes.

## Solution

The solution involves using techniques like pagination, virtualization, or windowing. See the `MyComponentSolution.js` for implementation with virtualization.