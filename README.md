# lambdakilo.github.io

The account lambdakilo was renamed to zululima. This site forwards every address on
lambdakilo.github.io to the same path on zululima.github.io, with the part after `#` kept, so
earlier Mismeet invite links and other old links still arrive. `index.html` and `404.html` are
the same page, since GitHub Pages serves `404.html` for every path that has no file.

`.well-known/` holds copies of the files on zululima.github.io: the iOS and Android app link
files, so Mismeet builds that list lambdakilo.github.io still open its invite links, and
`nostr.json`, so the Nostr address lambdakilo.github.io still verifies. A change to one of them
on zululima.github.io is copied here. `.nojekyll` makes GitHub Pages publish the `.well-known`
folder, which Jekyll would leave out.
