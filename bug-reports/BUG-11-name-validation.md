# BUG-11 — Name field rejects a valid hyphenated name

## Summary

The **Name** field does not accept a valid compound name containing a hyphen.

## Priority

**Standard**

## Status

**Open**

## Preconditions

1. Open the Yandex Samokat order form.

## Steps to Reproduce

1. Enter `Анна-Мария` in the **Name** field.
2. Remove focus from the field.

## Expected Result

The field accepts the valid name without displaying a validation error.

## Actual Result

The field is highlighted in red and displays a validation error indicating that a correct name should be entered.

## Environment

- Windows 11 Pro
- Google Chrome 149.0.7827.102 — 1920×1080
- Yandex Browser 26.4.3.894 — 1280×720

## Additional Information

The defect was identified during validation testing of the order form.
