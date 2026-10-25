# XNFT Preview Card

A responsive NFT preview card implemented with semantic HTML and CSS. The required Crio assessment script is not included in this starter package.

## Files

- `index.html` — the card structure and required text/links
- `style.css` — responsive layout, theme, typography, and hover states

## Use in the Crio project

1. Open the project folder `shubhamkumar25003-ME_FE_XNFT_PREVIEW_CARD` in your terminal.
2. Copy `index.html` and `style.css` into that project's root, preserving its `run_assessment.sh` and `assessment/` files.
3. The `<img>` elements use the conventional local paths `./images/image-equilibrium.jpg` and `./images/image-avatar.png`. The adjacent `<picture><source>` entries reference the same public challenge assets to make this standalone copy previewable even when those local image files are absent. If your starter assets are present, you can remove the `<source>` entries and use the local images directly.
4. Confirm the GitHub URL in the footer points to your own profile. The current link uses `https://github.com/shubhamkumar25003`, based on the supplied project-folder name.
5. Deploy the project, then create `submit.txt` in the project root containing only the deployed URL on one line.
6. Run the required assessment from the project root:

   ```bash
   chmod +x run_assessment.sh
   ./run_assessment.sh
   ```

Do not put a placeholder or a local development URL in `submit.txt`; it must contain the actual deployed URL.
