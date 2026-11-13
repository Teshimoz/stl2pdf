# STL → PDF 1:1

Print the side views of a 3D model (STL) to a PDF at **1:1 scale** on A4, A3 or Letter, to check the size and shape on paper before you print in plastic.

**Live tool:** https://teshimoz.github.io/stl2pdf/

## What it does

- Loads a binary or ASCII **STL** file. Drag it onto the page or press **Load STL**.
- Shows the three views of the cube side (Top, Front, Right) automatically. Press the cube to add its three views; up to **6 views** in total.
- Adds any **custom horizontal angle** (for example 45°, where 0° = front and 90° = right).
- Draws **outer contour** and **sharp edges** (edges where the surface bends more than the chosen curve angle). Hidden lines can be shown dashed (approximate).
- Puts views on **one shared sheet** when they fit, or on separate pages. Multi-page output has overlapping pages with page numbers and matching alignment lines.
- **Auto orientation** picks portrait or landscape, whichever needs fewer pages. Views can be turned 90° when that saves a page.
- Includes a **100 mm reference bar**. Measure it with a ruler: it must be exactly 100 mm.
- Paper background: millimetre paper (default), centimetre grid, or none. Frame opacity can be set from 20% to 80%.
- Units: millimetres, centimetres, metres or inches (converted to mm).
- Dark and light theme, switched with the squares in the corners.

## How to use

1. Press **Load STL** (or drag an `.stl` file onto the page).
2. Check the views and the preview. Remove a view with the large **X** in its frame. Switch a view to its opposite with the **arrow** in its frame, or use the **⟳** button in the top bar to switch all views.
3. Choose **A4, A3 or Letter** in the top bar.
4. Press **Download PDF**.
5. Print the PDF at **100% / actual size** (not "fit to page"). Check the 100 mm bar with a ruler before you rely on the size.

Keyboard and mouse: **Ctrl + Z** undoes view changes. **Ctrl + mouse wheel** zooms the preview.

## Privacy

Your STL file is processed in your browser and is **never uploaded**.

The page uses [GoatCounter](https://www.goatcounter.com/), a privacy-friendly counter that uses no cookies, to count anonymous visits, file loads, downloads and paper choices. No file content and no personal data is sent.

## Limitations

- Hidden lines are estimated: only back-facing edges are shown, and they are not checked against other parts of the model.
- Only triangle meshes are read. Colours and textures are ignored.
- Broken or open meshes can give wrong lines.
- Very large files can be slow.
- The PDF is 1:1 only when printed at 100% / actual size.

## Support

If the tool helped you, you can support it here: https://buymeacoffee.com/drozdovlevh

## Licence

Free to use. Copy and share it with a reference to the original tool. Licence: [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Disclaimer

The tool is provided **"as is"**, without warranty of any kind. The author is not responsible for any consequences of using it or its output, including wrong sizes, wasted material or damage. Use your own judgement.

## Repository contents

- `index.html`: the whole tool in one file (no build step, no server).
- `README.md`: this file.

## Publish on GitHub Pages

1. Create a public repository on GitHub (for example `stl-to-pdf`).
2. Upload `index.html` and `README.md` to it.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. After a minute or two, the tool is at `https://<your-username>.github.io/<repo>/`.

Keywords: stl to pdf, stl2pdf, print 2d from stl scale 1:1, fastest way to print stl side view to 2d in scale, stl side view to pdf, print 3d model actual size, 3d print size test.
