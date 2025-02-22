# React Router v6: Handling Special Characters in Dynamic Route Segments

This repository demonstrates a common issue and its solution when working with dynamic route segments and special characters in React Router v6.  The problem occurs when special characters (like +, *, ?, etc.) in a URL's dynamic segment aren't properly handled, leading to routing errors or unexpected behavior.

## Problem Description

When navigating to a route with a dynamic segment containing special characters, React Router v6 may fail to match the route correctly if the characters aren't URL-encoded or if the route definition doesn't account for them.

## Solution

The solution involves ensuring that the URL parameters are properly URL encoded before being used in the route and/or defining routes to handle various encodings of special characters.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the routing behavior with URLs containing special characters like `+`, `*`, and others.

## License

MIT