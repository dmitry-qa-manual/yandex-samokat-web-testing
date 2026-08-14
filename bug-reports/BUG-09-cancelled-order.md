# BUG-09 — Cancelled order remains available for viewing

## Summary

A cancelled order can still be opened by its order number on the order status page.

## Priority

**Critical**

## Status

**Open**

## Preconditions

1. An existing order is available in the system.
2. The user is on the order status page.

## Steps to Reproduce

1. Find an existing order by its order number.
2. Click **Cancel Order**.
3. Confirm the order cancellation.
4. Close the confirmation message about the successful cancellation.
5. Enter the order number of the cancelled order again.
6. Click **View**.

## Expected Result

The cancelled order is no longer available for viewing by its order number.

## Actual Result

The cancelled order can still be opened and is displayed on the order status page.

## Environment

- Windows 11 Pro
- Google Chrome 149.0.7827.102 — 1920×1080
- Yandex Browser 26.4.3.894 — 1280×720

## Additional Information

The defect was identified during functional testing of the order cancellation flow.
