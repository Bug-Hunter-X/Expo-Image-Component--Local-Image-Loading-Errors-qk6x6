# Expo Image Component: Local Image Loading Errors

This repository demonstrates a common error when using the Expo `Image` component to load local images. The error arises from incorrect URI formatting or premature file system access.

## Problem

The `Image` component fails to display local images due to issues with the provided URI and file system access timing.

## Solution

The solution involves ensuring the URI is correctly formatted with the `file://` prefix and handling asynchronous file system access with a state variable to ensure the file system is ready.