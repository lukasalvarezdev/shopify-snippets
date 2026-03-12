# Shopify Snippets

A collection of code snippets to paste into Shopify theme files.

Could be expanded to small standalone apps in the future.

## Snippets

### horizon/quantity-break.liquid

Syncs quantity input with variant selection based on quantity ranges.

**Setup:**
1. Create variant metafields in Shopify Admin > Settings > Custom data > Variants:
   - `custom.cantidad_minima` (integer)
   - `custom.cantidad_maxima` (integer)
2. Paste the snippet at the bottom of `snippets/product-information-content.liquid`

### horizon/whatsapp-button.liquid

Floating WhatsApp button in the bottom-right corner.

**Setup:**
1. Replace the phone number and pre-filled message in the href
2. Paste in `theme.liquid` before `</body>`
