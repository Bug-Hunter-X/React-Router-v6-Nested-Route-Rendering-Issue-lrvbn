# React Router v6 Nested Route Bug

This repository demonstrates a common error encountered when working with nested routes in React Router v6. The issue arises from incorrect nesting of route elements, preventing the nested component from rendering correctly.

## Bug Description
The bug is related to how nested routes are defined within the `Routes` component.  The nested route `/contact/details` is defined inside the parent route `/contact` correctly, but the incorrect nesting of routes causes the nested route to fail to render.

## Solution
The solution involves correctly structuring the nested routes to ensure proper rendering.  The change involves ensuring that the parent route is properly configured for nested routes.  See `bugSolution.js` for details.