# Create a truly transparent image

PNG supports transparency, but a PNG can still contain an opaque white background. A checkerboard baked into an image is also ordinary image content, not transparency.

1. Open the [transparent background maker](https://mattevia.com/transparent-background) and upload your photo.
2. Wait for the cutout, then choose Transparent.
3. Inspect the spaces between arms, laces, hair and other details.
4. Export PNG or WebP. Do not choose JPG if you need transparency.
5. Reopen the file in an editor and place a colored layer beneath it. The color should show through the empty areas.

## Troubleshooting

| Symptom | What to check |
| --- | --- |
| The image looks white in a viewer | The viewer may have a white canvas; test a colored layer underneath. |
| Squares remain visible everywhere | The source may contain a printed checkerboard; changing formats cannot remove it. |
| White fringe on a dark background | Inspect the edge at 100%; try a clearer source with stronger separation. |
| Download has different dimensions | Processing and result-file limits may cause proportional resizing. |

An already transparent PNG usually does not need another removal pass; another pass may alter its edges.

[Quality checklist](quality-checklist.md) · [Back to README](../README.md)
