# Proposed changelog entries for review

These undated proposals are pending verification and are not release announcements. This directory is excluded from Mintlify by `.mintignore`. Do not move these entries into the published changelog until the checks below are complete.

## Suggest Shopify categories and tailor required fields

Proposed copy:

Generate a suggested Shopify product category, review it, and correct the selection when needed. Set field requirements by product role or category so a parent product and its variants can have different requirements.

Remaining verification:

- Confirm a Shopify category suggestion can be generated and saved in a configured workspace.
- Confirm a configured role/category example shows the intended required fields. This describes field requirements, not a publishing block.

## Choose Shopify sales channels from your catalog

Proposed copy:

Import your current Shopify sales-channel selections, review them in the catalog, then export your changes. Reconnect Shopify to grant the required access before using sales-channel fields.

Export replaces the complete mapped selection. A blank mapped selection removes all sales-channel availability. Shopify Markets and B2B catalogs are not included.

Remaining verification:

- Reconnect and import have been demonstrated; confirm the configured export replaces the selection as expected.
- Confirm a blank mapped selection removes availability as expected before publishing these instructions.

## Keep Wayfair templates aligned with updated requirements

Proposed copy:

When supported Wayfair requirements change, affected account templates refresh to match. You no longer need to use **Refresh Existing** manually for those supported changes.

Remaining verification:

- Confirm a supported requirements change successfully refreshes the affected account's existing template.
- Check the resulting fields and order before announcing this behavior.
