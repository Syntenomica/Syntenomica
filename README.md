![Syntenomica — Scientific software, thoughtfully built](assets/banner.svg)

I build tools that make scientific images and data easier to explore, compare and document. My current work focuses on microscopy workflows, local image processing and protein sequence exploration.

## Projects

### Syntenomica
A microscopy workspace for reviewing focal planes, comparing recordings, computing focus composites and documenting observations.

- **Android:** the original mobile application.
- **Ubuntu:** a native desktop preview with local projects, manual measurements and relative focus Relief.
- Application source repositories are currently private.

#### Android closed test

Syntenomica 0.11.0 (build 31) is available to enrolled testers on Google Play. I’m looking for volunteers who use Android 8.0 or later. Can you import a short focus sweep, mark eight circles on one frame, and find those eight observations in your export? The six-second practice clip comes with English and Hungarian instructions. You can also try your own microscope recording. [Download the practice clip and instructions](https://github.com/Syntenomica/Syntenomica/raw/refs/heads/main/assets/android-closed-test.zip)

1. To volunteer, privately email the Google Play address you want added to the test. [Request an invitation at syntenomica@gmail.com](mailto:syntenomica@gmail.com?subject=Syntenomica%20Android%20closed%20test)
2. After you receive confirmation, open the opt-in page with that same account and install the app. [Join on Google Play](https://play.google.com/apps/testing/com.syntenomica.trace) · [Install from the Play Store](https://play.google.com/store/apps/details?id=com.syntenomica.trace)
3. Please stay enrolled for at least 14 consecutive days. I’d like to hear which step worked and where you got stuck. Your phone model, Android version and app version will help me reproduce issues. [Send feedback](mailto:syntenomica@gmail.com?subject=Syntenomica%20test%20feedback) · [Privacy information for testers](https://syntenomica.github.io/privacy/#email)

<details>
<summary>Jelentkezés magyarul</summary>

A Syntenomica ingyenes zárt tesztje Android 8.0 vagy újabb telefonon érhető el. Mikroszkóp nélkül is kipróbálhatod.

1. Írd meg privát e-mailben, melyik Google-fiókkal használod a Play Áruházat. Erre a címre küldök visszaigazolást, amikor felvettelek a tesztelői listára. [Jelentkezés e-mailben](mailto:syntenomica@gmail.com?subject=Syntenomica%20tesztjelentkez%C3%A9s)
2. A visszaigazolás után ugyanazzal a Google-fiókkal nyisd meg a teszt oldalát, csatlakozz, majd telepítsd az appot. Kérlek, maradj feliratkozva legalább 14 egymást követő napig. [Csatlakozás a teszthez](https://play.google.com/apps/testing/com.syntenomica.trace) · [Telepítés a Play Áruházból](https://play.google.com/store/apps/details?id=com.syntenomica.trace)
3. Csomagold ki a próbavideót, majd importáld az appba. Jelöld meg a nyolc kört egy képkockán, és nézd meg, megtalálod-e mind a nyolc jelölést az exportált fájlban. Írd meg, melyik lépés ment könnyen, vagy hol akadtál el. A telefon típusa, az Android és az app verziója segít utánajárni. [Próbavideó és magyar útmutató](https://github.com/Syntenomica/Syntenomica/raw/refs/heads/main/assets/android-closed-test.zip) · [Visszajelzés](mailto:syntenomica@gmail.com?subject=Syntenomica%20tesztvisszajelz%C3%A9s)

</details>

### [PRISM · Protein Intelligence Suite](https://github.com/Syntenomica/PRISM)
A Flask/Biopython application for exploring sequence-derived protein descriptors, comparing variants and exporting reports. The public repository includes setup instructions and the limits of its heuristic interpretations.

## How I approach the work

Clear interfaces, traceable processing and honest scientific limits. A visualization should help explain the data without implying more precision than the method supports.

**Working with:** Python · Kotlin · Qt/PySide6 · OpenCV · NumPy/SciPy · ONNX Runtime · Flask · Biopython

[PRISM source](https://github.com/Syntenomica/PRISM) · [Syntenomica privacy policy](https://syntenomica.github.io/privacy/)
