# AMU Website — Product Images

## How this works

Every product card on the Catalogue page looks for an image at:

```
images/<TA_CODE>.jpg
```

For example, the "Electromagnet" card (code `AMU_TA_G8001`) looks for `images/AMU_TA_G8001.jpg`.

**If that file doesn't exist yet, the website automatically shows a "Photo pending" placeholder instead — you don't need to touch any code.** As soon as you add a correctly-named image to this folder and re-upload the site (or push to GitHub), the real photo takes over automatically.

## Adding a new product photo

1. Take or export your product photo as a `.jpg`.
2. Rename it to match the product's TA_CODE exactly, e.g. `AMU_TA_G7002.jpg` for "Working of a DC Motor".
3. Drop it into this `images/` folder, replacing nothing else.
4. Upload/commit the updated folder to GitHub (or wherever the site is hosted).
5. Refresh the live site — the photo should now appear in place of the placeholder.

## Currently has real photos

| TA_CODE | Product |
|---|---|
| `AMU_TA_G6001` | Magnetic Material Finder |
| `AMU_TA_G6002` | Magnetic Levitation |
| `AMU_TA_G6003` | Magnetic Field Pattern |
| `AMU_TA_G10011` | Oersted Experiment |
| `AMU_TA_G10013` | Field due to Circular Coil |

All other 36 products currently show the "Photo pending" placeholder until a matching image is added here.

## Notes

- Recommended photo size: roughly 1000×750px (4:3), under ~500KB, for reasonable page-load speed.
- File format: `.jpg` only (the site currently looks for `.jpg` specifically — if you have `.png` files, convert them or ask for the code to be updated to also check `.png`).
- Do not use another company's product photography — see the note left in the chat about this. Photos here should be of AMU's own products.
