# Employee photos (replace the right-side image)

## Goal
Take an employee photo, upload it, and show it on the RIGHT SIDE of the desktop card (instead of the default Highlight image).

## What changed
- `employees.csv` now supports a `photo` column.
- If `photo` is blank, the site uses `assets/right-panel.png`.
- If `photo` has a value, it replaces the right-side image for that employee.

## Workflow
1) Take a photo.
2) Crop to square (optional) and resize to ~600px wide.
3) Save as JPG and keep under ~400KB if possible.
4) Upload into your repo: `assets/people/`
5) In `employees.csv`, set `photo` to:
   `assets/people/<slug>.jpg`

## Examples
- assets/people/kayden-johnson.jpg
- assets/people/taryn-swayze.png

## Tip
If you have two employees with the same name, set a unique `slug`.
