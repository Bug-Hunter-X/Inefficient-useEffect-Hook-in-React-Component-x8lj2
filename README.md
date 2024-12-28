# Inefficient useEffect Hook in React Component

This repository demonstrates a common performance issue in React applications involving the `useEffect` hook. The provided code shows how an incorrectly implemented `useEffect` hook leads to unnecessary re-renders, impacting the performance of the component.

## Problem

The `useEffect` hook, without specifying dependencies, runs after every render.  In the example `MyComponent`, this leads to an excessive number of console logs and unnecessary re-renders, which is inefficient for the application.