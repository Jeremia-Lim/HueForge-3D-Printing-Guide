# 🎨 HueForge Color Core Guide: Understanding Colors and Layer Transitions

## Introduction

One of the biggest challenges when learning HueForge is understanding how filament colors interact and how layer transitions affect the final artwork.

Have you ever imported an image, selected your filament colors, and wondered why the preview looks completely different from the original?

Maybe your image looks too blue, your highlights disappear, or adjusting one color makes everything else look worse.

This tutorial will help you understand how to work with Color Core and filament layer transitions to improve your HueForge prints.

## Step 1: What Is Color Core?

Color Core is part of HueForge's color configuration workflow.

It helps you work with the filament color information used to generate your artwork.

When adjusting your project, it's important to distinguish between:

- **Filament profiles:** Describe the colors and optical properties of your materials.
- **Filament palette:** The colors selected for your project.
- **Layer transitions:** Determine where one filament stops and another begins.
- **Color preview:** Simulates how your chosen filament stack may appear.

These settings work together, but they do not all perform the same function.

**Beginner Tip:** Selecting a filament color is not the same as assigning that filament to a specific layer height.

## Step 2: Start With the Filaments You Own

Before making changes, identify your available filament colors.

For example, if you're creating an underwater portrait, your available palette might include:

| Filament | Possible Use |
|---|---|
| Black | Dark shadows and outlines |
| Dark Blue | Deep water and shadows |
| Light Blue | Midtones and water |
| White | Highlights and bright areas |
| Brown | Warmer details |

You do not need to use every available filament.

Sometimes, removing a color produces a cleaner result.

### How to Begin

1. Open your image in HueForge.
2. Review your selected filament profiles.
3. Locate the Color Core controls in your version.
4. Confirm that the filament profiles match your available materials.
5. Review the initial preview before making adjustments.

## Step 3: Understand Layer Transitions

HueForge creates filament paintings by stacking thin layers of filament.

The height at which a filament changes affects the appearance of the finished image.

For example, imagine a project using:

- Black for the darkest regions
- Blue for cooler midtones
- White for brighter highlights

The resulting appearance depends on the filament order, the number of layers assigned to each color, and the transmission distance (TD) of each filament.

### Why Layer Height Matters

If you increase the thickness of a particular color, that filament may have a stronger visual influence.

If you reduce its thickness, underlying colors may become more visible.

However, the result also depends on the opacity of the filament and the colors beneath it.

**Important:** A HueForge preview is a simulation. Your actual print may differ because of filament properties, lighting, and print settings.

## Step 4: How to Adjust Color Transitions

Start with a simple filament combination.

1. Select a project with a recognizable subject.
2. Choose a small set of filament colors.
3. Review the current layer transitions.
4. Adjust one transition at a time.
5. Observe how the preview changes.
6. Compare the new result with the original image.
7. Save configurations that produce better results.

### Example: Fixing an Image That Looks Too Blue

Imagine you're creating a portrait surrounded by water.

You select blue filament to create an underwater effect, but suddenly the entire subject looks blue.

This can happen when blue layers influence areas that should remain lighter or warmer.

Try the following:

1. Review how many layers are assigned to blue.
2. Experiment with reducing the blue layer range.
3. Check whether your white filament produces sufficient highlights.
4. Consider introducing another filament for warmer tones.
5. Compare each change before making another adjustment.

**Beginner Tip:** Adding more colors does not always improve an image. Sometimes a simpler palette creates better contrast and detail.

## Step 5: Understanding Slider Limitations

When adjusting filament transitions, you may notice that certain sliders cannot move beyond a specific point.

This is often intentional.

HueForge must maintain a valid layer arrangement, and transition controls may be constrained by adjacent transitions, the model's height, or the available layer positions.

### What to Do When a Slider Won't Move

1. Check the position of nearby transition controls.
2. Review the available layer range.
3. Confirm your selected layer height.
4. Consider adjusting an adjacent transition.
5. Check whether the current filament order supports your intended effect.

Do not assume the software is malfunctioning simply because a slider cannot move farther.

## Step 6: Improving Portrait Details

Portraits can be particularly challenging because small changes in color and contrast affect recognizable features.

When adjusting your filament configuration, focus on:

- **Eyes:** Preserve contrast around the eyes.
- **Hair:** Maintain separation between highlights and shadows.
- **Skin:** Avoid allowing one cool or dark filament to dominate.
- **Background:** Keep enough contrast between the subject and surrounding artwork.
- **Highlights:** Use appropriate filament transitions to preserve bright areas.

### Beginner Tip

When working with a portrait, prioritize recognizable facial features before trying to match every color in the original photograph.

## Step 7: Save and Compare Your Results

Instead of repeatedly modifying one configuration, save different versions of your project.

For example:

- `portrait-test-01`
- `portrait-test-02`
- `portrait-blue-adjustment`
- `portrait-final`

Record what changed between versions.

| Version | Adjustment | Result |
|---|---|---|
| Test 1 | Initial filament configuration | Baseline preview |
| Test 2 | Reduced blue layer range | Compare subject visibility |
| Test 3 | Adjusted white transition | Compare highlight clarity |
| Test 4 | Modified warm-tone filament | Compare color balance |

These are example experiments, not guaranteed outcomes.

## Step 8: Prepare for Bambu Studio

Once you're satisfied with the HueForge preview:

1. Save your HueForge project.
2. Export the printable model.
3. Record the required filament change heights or layers.
4. Import the model into Bambu Studio.
5. Match your slicer layer height to the HueForge configuration.
6. Configure filament changes according to the exported instructions.
7. Slice the model and inspect the preview.

Always confirm that the correct physical filaments are assigned before printing.

## Troubleshooting

| Problem | What to Check |
|---|---|
| Entire image looks blue | Blue layer range, filament order, and TD |
| White highlights disappear | White filament opacity and transition height |
| Slider cannot move farther | Adjacent transitions and layer limits |
| Portrait loses detail | Source image contrast and color configuration |
| Colors look muddy | Filament order, TD values, and overlapping color effects |
| Preview differs from print | Physical filament properties and slicer settings |

## Key Takeaways

- Filament color and filament layer position are different settings.
- Transmission distance influences how colors interact.
- Adjust one transition at a time to understand its effect.
- More filament colors do not necessarily produce better artwork.
- Save multiple versions to compare your experiments.
- Always verify your Bambu Studio configuration before printing.

## What's Next?

Now that you've explored Color Core and layer transitions, it's time to prepare your artwork for printing.

**Next Tutorial:** [Exporting HueForge Projects to Bambu Studio](05-bambu-studio.md)

---

*Part of the
