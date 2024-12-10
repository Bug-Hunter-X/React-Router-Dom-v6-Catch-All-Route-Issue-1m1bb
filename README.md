# React Router Dom v6 Catch All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6.  The catch-all route, intended to handle all unmatched routes, unexpectedly fails to match some routes resulting in unexpected behavior or errors.

The problem occurs because of an improper placement or definition of the catch-all route, leading to some routes not being caught, causing unexpected behavior or crashes.

## Solution
The solution involves carefully positioning and potentially refactoring the catch-all route to ensure all unmatched paths are correctly handled.  The solution file provides the improved implementation.