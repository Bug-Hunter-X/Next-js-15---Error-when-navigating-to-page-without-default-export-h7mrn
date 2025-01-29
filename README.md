# Next.js 15 - Error when navigating to page without default export

This repository demonstrates a common error encountered in Next.js 15 applications when navigating to a page that does not export a default function component.  The error message is often unclear.  This example shows how to reproduce the issue and provides a solution.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.

You should see an error in your browser's console.

## Solution

Ensure that all your pages export a default function component, even if it's just a placeholder.