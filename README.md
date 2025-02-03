# Expo CLI Android Build Failure: Unclear Errors

This repository demonstrates a common, yet difficult-to-diagnose, error encountered when building Android apps using the Expo CLI. The error manifests as unclear error messages during the build process, often triggered by the `expo prebuild` command.  This is typically due to underlying issues within the project's Android configuration or dependencies.

## Problem

The problem is that the Expo CLI Android build process fails without providing sufficient information to pinpoint the exact cause.  The error messages are often generic and don't directly indicate the problematic dependency or configuration setting.

## Solution

The solution involves carefully analyzing the detailed build logs (often quite long) to identify the underlying cause. It also involves verifying the correctness of the project's Android configuration and ensuring all required dependencies are properly installed and configured.

This repo contains example code to reproduce (in `bug.js`) and solve (in `bugSolution.js`) this problem.  Consult the detailed error messages to understand the specifics of your situation.  Cleaning and rebuilding the Android project is also a common first step to resolve many obscure build issues.