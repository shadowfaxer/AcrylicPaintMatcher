This app acst as a digital assistant for artists, helping them translate a color observed in an image into a tangible paint mixture using Winsor & Newton acrylics.

Allows user to select an image or take a photo, then select a spot on the image you want to match. The app then reports the RGB at that spot and gives a simple recipe to produce that colour.

# Limited Paint Palette

Uses a small, fixed palette of Winsor & Newton paints with placeholder RGB values.

# Simplified Mixing Logic

For a target color, the app trys to find the closest 2-paint and 3-paint combinations from the predefined palette.
"Mixing" will be simulated by weighted averaging of RGB values. This is a significant simplification of real paint mixing but is a common approach for digital approximations.
It trie various ratios for these mixes (e.g., 1:1, 2:1, 1:2, etc.) Along with the calulated colour and its "recipe", the color difference measured as Euclidean distance in RGB space from the target colour is also reported.
