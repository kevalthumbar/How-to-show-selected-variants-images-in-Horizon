# Horizon Theme Update Guide (v3.5.1)

## Current Theme
**Horizon 3.5.1**

## Setup Instruction
Replace Horizon theme files with the files from this repository.

---

## How It Works

With the new logic in place, the theme is extremely flexible. If you have multiple images for a variant (e.g., Black), there are two ways to ensure they group correctly.

You can choose whichever method fits your workflow.

---

## Method 1: Naming Image Files (Before Upload)

Before uploading images to Shopify, include the color name anywhere in the file name.

**The system is case-insensitive**, so all of the following will work:

- `black-front.jpg`
- `shoes_black_side.png`
- `Black-hero-shot.jpg`
- `product1-black.jpg`

### Tip
Make sure the file name matches the exact variant name.

Example:
- Variant name: `Matte Black`
- File name: `matte-black-1.jpg`

---

## Method 2: Using Shopify Alt Text (After Upload)

If images are already uploaded, you can assign them using **Alt Text**.

### Steps:
1. Go to **Shopify Admin → Products**
2. Select the product
3. Scroll to the **Media** section
4. Click on an image
5. On the right panel, click **Add alt text**
6. Enter the variant name (e.g., `Black`)
7. Click **Save**

### How It Works
The system checks:
- Image file name
- Alt text

If either contains the variant name, the image will automatically be grouped with that variant in the carousel.

---

## Shared Images (Neutral Images)

For images that should appear for all variants (e.g., size chart, lifestyle shots, tags):

### Option 1: Neutral File Names
- `size-chart.jpg`
- `lifestyle.jpg`

### Option 2: Neutral Alt Text
- `Size Guide`
- `Product Detail`

### Behavior
If no variant color is detected in the file name or alt text:
- The image will be shared across all variants
- It will not be hidden when switching variants

---

## Summary

- Supports both **file name** and **alt text** matching
- Case-insensitive matching
- Automatically groups images per variant
- Neutral images are shared across all variants

---
