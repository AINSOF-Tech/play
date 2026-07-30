# AINSOF — listen page

The page behind every listen link the AINSOF agent hands out.

**One page for the whole catalogue.** The cue is read from the address fragment
and everything else — artwork, credits, audio — is fetched live, so a new album
works the day it lands with nothing to regenerate.

```
https://play.ainsof.io/#AIN-CAT_057_001
```

It shows the album art, the title, the album and catalogue number, the composer,
the tempo and the length, and draws a **real** waveform: the file is decoded with
the Web Audio API and the peaks are measured from the samples. Click the waveform
to seek.

Every preview it plays is watermarked. Previews are for auditioning; they are not
licensed for release.

Nothing external loads — no CDN, no web fonts, no analytics. The only two origins
this page ever contacts are the AINSOF API and AINSOF storage.

**Licensing:** [or@ainsof.io](mailto:or@ainsof.io)

---

AINSOF is a boutique production music library. We control both the recordings and
the publishing, which is why our agent can answer a rights question directly.
