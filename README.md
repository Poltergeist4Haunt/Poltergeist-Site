# Poltergeist site

the download page for poltergeist. just one `index.html`, no build step.

live at https://poltergeist4haunt.github.io/Poltergeist-Site/

## folders

- `downloads` put `Poltergeist-win-x64.zip` and `Poltergeist-mac.zip` here, the buttons link to these names
- `meta` the preview image people see when the link gets shared (`og-image.png`, `og-card.html` is what it's made from)
- `shots` optional. drop `capture.png`, `editor.png`, `record.png`, `video.png`, `upload.png`, `settings.png` in and they replace the little animated demos

## updating

new version? swap the zips in `downloads` and change the sizes in `index.html` if they moved a lot (search for `77` and `2&nbsp;MB`).

github blocks files over 100mb so keep the zips under that.

pages caches for a few minutes so give it a sec after pushing.
