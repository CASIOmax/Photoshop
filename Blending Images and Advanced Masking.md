# Blending Images and Advanced Masking

This document covers the techniques of blending images, using masks, advanced masking techniques, and working with the Lasso Tool in Photoshop.

---

## Blending Two Images

If you want to blend two images, such as a before and after comparison, follow these steps:

1. **Place two images** on top of each other.
2. **Create a mask** on the top image.
3. Use the **Brush Tool** to blend the images.
   - The **foreground color** determines the action:
     - **Black**: Removes the area of the top image in the mask, revealing the bottom image.
     - **White**: Restores the area of the top image.
   - Use the **double arrow** to switch between black and white.

**Caution**: Make sure to select the **mask** of the top image, not the image itself.

---

## How Masking Works

Masking allows you to hide or reveal parts of an image. You create a mask on a layer, then use the **Brush Tool** to paint:
- **Black**: Hides parts of the image.
- **White**: Restores hidden areas of the image.

Masks are non-destructive, so you can easily undo or modify the mask without permanently altering the image.

---

## Putting Weave Text In and Out of an Image

To make text weave in and out of an image:
1. **Create a mask** on the image.
2. **Remove sections** of the image around the text using the **Brush Tool**, so parts of the text appear behind the image and others in front.

---

## Advanced Masking

1. Select the image using the **Quick Selection Tool** and then create a mask.
2. Click on **Select and Mask** for more precise masking options:
   - **Change the view** to black if working with white-rich images.
   - Use the **Refine Edge Brush Tool** (2nd tool in the left toolbar) for complex edges like hair or fur.
   - For simpler areas, use a standard **circular brush**.
3. Optionally, use **Decontaminate Colors** to clean up any unwanted color fringing along the edges.

---

## Lasso Tool

The **Lasso Tool** allows you to quickly select and move elements within an image. It's faster than the Quick Selection Tool for irregular shapes:
- Use the **Lasso Tool** to make a freehand selection.
- The **Polygonal Lasso Tool** is ideal for more precise selections, particularly when working with straight-edged objects.
- The **Magnetic Lasso Tool** helps with snapping to object edges for easier selections.

The Lasso Tool is especially helpful for dealing with shapes, illustrations, or other complex objects.

---

This markdown file provides a quick overview of blending, masking, and advanced selection techniques in Photoshop.
