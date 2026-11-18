# 🎨 Understanding Filament Colors in HueForge

## Introduction

One of the most exciting features of HueForge is its ability to create colorful 3D printed artwork using layers of filament.

Unlike traditional multi-color 3D printing, where different colors are often printed side by side, HueForge uses thin layers of filament stacked on top of one another.

The colors you see depend on the filament's properties, layer thickness, and how much light passes through the material.

In this tutorial, you'll learn how to select filament colors, understand transmission distance (TD), arrange filament layers, and improve color accuracy.

## Step 1: Understand How HueForge Uses Colors

HueForge creates filament paintings by combining different filament colors at different layer heights.

When light passes through upper layers of filament, the colors underneath can influence the final appearance.

For example:

- **White:** Often useful for brightening highlights and creating lighter details.
- **Black:** Commonly used for dark backgrounds, shadows, and contrast.
- **Blue:** Can create water, skies, shadows, or cool-toned artwork.
- **Brown:** Useful for earth tones, hair, wood, and warm shadows.
- **Gray:** Can help create smoother transitions between black and white.

**Beginner Tip:** You don't necessarily need every color visible in the original image. A carefully selected palette can produce a recognizable result with fewer filaments.

## Step 2: What Is Transmission Distance (TD)?

Transmission Distance, or **TD**, describes how far light can travel through a filament before its intensity is significantly reduced.

This property is important because two filaments that appear to be the same color on a spool may behave differently when printed in thin layers.

### Understanding TD

- **Lower TD:** The filament is more opaque and tends to cover underlying colors more quickly.
- **Higher TD:** The filament allows more light through, making underlying colors more influential.

For example, an opaque white filament may brighten an image differently from a more translucent white filament.

### Why TD Matters

Incorrect TD values can cause:

- Colors that appear too dark or too light
- Unexpected color blending
- Loss of fine details
- Differences between the HueForge preview and finished print

**Important:** TD is specific to the filament. Brand, material, pigmentation, and even different shades can affect its behavior.

For accurate results, use measured TD values when available rather than assuming every filament of the same color behaves identically.

## Step 3: Select Your Filament Colors

Before adjusting your image, identify the filament colors you actually own.

1. Open your project in HueForge.
2. Locate the filament selection controls.
3. Review the available filament profiles.
4. Select profiles matching your physical filament.
5. Check their TD values.
6. Review the updated preview.

### Example: Creating an Ocean-Themed Portrait

Imagine you're printing a portrait with a blue underwater background.

You might experiment with:

| Filament | Possible Purpose |
|---|---|
| Black | Deep shadows and contrast |
| Dark blue | Darker water areas |
| Light blue | Water and midtones |
| White | Highlights and bright details |
| Brown | Warmer tones, where needed |

These are possible palette choices, not a guaranteed layer order. The correct sequence depends on your image, filament properties, and desired effect.

## Step 4: Understand Filament Layer Order

HueForge uses filament stacking to create different visual effects.

The order of your filament layers matters because upper layers interact with the colors beneath them.

For example, adding several layers of blue over a dark base may create a deeper blue appearance.

Adding lighter or more opaque filament layers may help create highlights, depending on the material.

### Common Beginner Mistake

Using too much of one color can overwhelm the image.

If your portrait looks entirely blue, the issue may be the thickness or placement of your blue layers rather than the original image.

**Solution:** Experiment with the layer transition positions and compare the preview after each adjustment.

## Step 5: Experiment With Color Core

HueForge includes Color Core controls that affect how filament colors are represented and combined in the project.

When working with Color Core:

1. Review the filament colors in your current configuration.
2. Check which filament profiles are being used.
3. Experiment with the available color controls.
4. Observe changes in the preview.
5. Compare different configurations before exporting.

The exact controls may vary depending on your HueForge version.

**Beginner Tip:** Change one setting at a time. This makes it easier to identify which adjustment improves or worsens the image.

## Step 6: Match HueForge Colors With Bambu Studio

After configuring your colors in HueForge, you'll need to ensure that your slicer uses the intended filaments.

1. Export your HueForge model.
2. Record the filament change heights or layer instructions.
3. Import the model into Bambu Studio.
4. Configure the physical filaments you plan to use.
5. Set the required filament changes.
6. Slice the model and inspect the preview.

**Important:** The filament colors displayed in Bambu Studio do not automatically guarantee the correct physical filament is assigned.

Verify the actual filament assignments before printing.

## Step 7: Improve Color Accuracy

If your finished print doesn't match the HueForge preview, consider these adjustments:

- Verify that the filament profiles match your physical materials.
- Check the TD values.
- Review the order of filament changes.
- Adjust the number of layers assigned to each color.
- Confirm the slicer's layer height matches your intended configuration.
- Print a smaller test before attempting a large project.

## Troubleshooting Common Color Problems

| Problem | Possible Cause | Suggested Fix |
|---|---|---|
| Image looks too blue | Blue layers dominate the image | Adjust blue transition heights |
| Colors appear muddy | Unwanted blending between layers | Experiment with filament order and TD |
| Image looks too dark | Insufficient light transmission or dark layers | Review TD and layer thickness |
| Highlights disappear | Bright layers are too thin or poorly positioned | Adjust highlight transitions |
| Printed colors differ from preview | Filament properties or slicer settings differ | Verify profiles and print configuration |

## What's Next?

Now that you understand filament selection and transmission distance, the next tutorial will explore Color Core and layer transitions in more detail.

**Next Tutorial:** [Understanding Color Core in HueForge](04-color-core.md)

---

*Part of the HueForge 3D Printing Guide — an independent educational resource for beginners learning multi-color 3D printing.*
