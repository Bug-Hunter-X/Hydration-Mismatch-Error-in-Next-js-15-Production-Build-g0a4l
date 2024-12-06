# Next.js 15 Hydration Mismatch Bug

This repository demonstrates a hydration mismatch error encountered in a Next.js 15 application running in production mode.  The error occurs despite a seemingly simple functional component. This bug report includes both the problematic code and a solution.

## Problem

A hydration mismatch error is thrown during the client-side hydration of a functional component that simply renders an h1 tag. The error only manifests in the production build, not during development.

## Solution

The solution involves ensuring the client-side rendering matches the server-side rendering precisely. The details are provided in `bugSolution.js`.