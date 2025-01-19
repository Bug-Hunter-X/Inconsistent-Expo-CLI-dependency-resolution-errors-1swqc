# Inconsistent Expo CLI Dependency Resolution Errors

This repository demonstrates a bug where the Expo CLI development server fails to start due to inconsistent and sporadic dependency resolution errors. The errors occur without any apparent pattern, even with a seemingly correct `package.json` and `package-lock.json`.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `expo start`.
4. Observe the inconsistent dependency resolution errors that prevent the development server from starting.

## Solution

The solution involves a combination of techniques to ensure clean dependency resolution, detailed in `expoBugSolution.js`.

This issue highlights the importance of diligent dependency management and the potential for hidden issues in the Expo CLI's dependency resolution process.