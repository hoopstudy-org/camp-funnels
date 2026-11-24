# HoopStudy Summer Camps funnel

One page serving all three camps. Link to a specific camp with `?camp=pg`, `?camp=elite` or `?camp=girls`.

## Edit before launch
All content lives in the settings block at the top of the `<script>` in `index.html` (search for `TODO`):
- `CONFIG.casselsPhone` / `casselsDisplay`: Cassels' real number
- `CONFIG.offerClaimed`: set above 0 to show the "X of 100 left" bar
- `CAMPS.*.sessions`: real dates and grades per camp
- `CLIPS[].video`: Vimeo/YouTube embed links for the testimonial tiles

## Images
Everything in `assets/` is referenced by relative path, so keep the folder next to `index.html`.
Swap a photo by replacing the file with one of the same name, or change the `src` in `index.html`.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000
