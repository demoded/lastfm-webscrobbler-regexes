# lastfm-webscrobbler-regexes

These are Regex/Bulk edits for [Web Scrobbler](https://chromewebstore.google.com/detail/web-scrobbler/hhinaapppaileiechjoiifaancjggfjm) chrome extension.
Go to [Options] -> [Edits] -> Regex/Bulk edits and import the json file

Rules:
- drop " - Single" tail from album
- drop " - EP" tail from album
- drop " vinyl" from track name
- drop " - 1980 Vinyl LP" from track name applicable to any 4 digits
- drop " • Vinyl • Yamaha PX-3 • V15 Type IV SAS/B • Yamaha C-4" from track name. this is for the [Spinnin' Grooves](https://www.youtube.com/@spinningrooves839) channel
- drop " - Topic" from the artist name
