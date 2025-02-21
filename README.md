# Unexpected Null Values in foo function

This repository demonstrates a common JavaScript bug involving the improper handling of null values in a function. The `foo` function does not explicitly check for null values in its parameters, which can lead to errors or unexpected behavior.

## Bug Description

The `foo` function fails to account for null values passed as arguments. This can lead to errors (e.g., `TypeError`) if the function attempts to perform operations on a null value. This also affects the output and can cause unexpected behavior.

## Solution

The provided solution enhances the function to explicitly check for null values and return null if encountered. This ensures that unexpected null values are handled gracefully without causing errors.