# HueForge 3D Printing Guide 🎨

### Beginner-Friendly HueForge Tutorial | Bambu Studio | Multi-Color 3D Printing

Learn how to turn ordinary photographs and digital artwork into colorful, layered 3D prints using HueForge and Bambu Studio.

This repository documents my journey learning HueForge, including successful prints, mistakes, troubleshooting, and practical techniques for improving image clarity and color accuracy.

## What Is HueForge?

HueForge is software that transforms 2D images into layered 3D printable artwork. By controlling filament colors, layer thicknesses, and color transitions, you can produce detailed images with a standard FDM 3D printer.

## Getting Started

### Step 1: Choose Your Image

Start with a photograph or illustration that has:
- Clear subjects
- Good contrast
- Recognizable details
- Colors that can be approximated with your available filaments

### Step 2: Import Into HueForge

1. Open HueForge.
2. Import your image.
3. Choose the desired dimensions.
4. Review the initial color and depth preview.

### Step 3: Configure Your Filaments

1. Identify the filament colors you own.
2. Select appropriate filament profiles.
3. Review their transmission distance (TD) values.
4. Adjust filament choices to improve the preview.

**Tip:** Filament transparency affects how underlying colors appear. Choosing the correct color alone does not guarantee an accurate result.

### Step 4: Adjust Color Core and Layer Transitions

Use HueForge's layer and color controls to experiment with where filament transitions occur.

Compare different configurations before selecting the best result.

### Step 5: Export Your Project

Export the generated model and save the recommended layer-change information.

Keep a copy of your HueForge project for future adjustments.

### Step 6: Prepare in Bambu Studio

1. Import the exported model.
2. Configure your printer and filament profiles.
3. Match filament changes to the required layers or heights.
4. Confirm the sliced preview matches your intended color sequence.
5. Review estimated print time and material usage.

### Step 7: Print and Evaluate

After printing, compare the final result with the original image and HueForge preview.

Document:
- Color accuracy
- Detail preservation
- Layer alignment
- Filament consumption
- Changes needed for the next print

## Troubleshooting

### My print looks too dark or blue

Review filament order, TD values, and color transition heights. Experiment with lighter filaments and compare previews.

### My image loses facial details

Try a higher-quality source image, improve contrast, and adjust the filament transitions.

### My filament colors do not match

Check that HueForge's filament selections and Bambu Studio's assigned filament slots are consistent.

## Future Development

- Filament compatibility reference
- Printable troubleshooting examples
- Python-based filament cost calculator
- Print optimization experiments
- Before-and-after project gallery

## Contributing

Found a useful HueForge technique or troubleshooting solution? Contributions, suggestions, and documented print experiments are welcome.

## Disclaimer

This is an independent community learning project and is not affiliated with or endorsed by HueForge or Bambu Lab.
