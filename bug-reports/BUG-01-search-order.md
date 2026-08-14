# BUG-01 — Search by order number does not work with Enter

## Summary

Searching for an order by its correct order number does not work when pressing the `Enter` key.

## Priority

**Standard**

## Status

**Open**

## Preconditions

1. Open the Yandex Samokat application.
2. An order with a valid order number exists in the system.

## Steps to Reproduce

1. Open the **Order Status** page.
2. Enter a valid order number in the **Order Number** field.
3. Press `Enter`.

## Expected Result

The order search is performed and information about the found order is displayed.

## Actual Result

After pressing `Enter`, the order search is not performed and information about the order is not displayed.

## Environment

- Windows 11 Pro
- Google Chrome 149.0.7827.102 — 1920×1080
- Yandex Browser 26.4.3.894 — 1280×720

## Additional Information

The issue was reproduced during web application testing.
