---
layout: article
title: Information
key: page-info
---

## Website vs. Google Docs Translation Index
The [Google Docs Translation Index](https://docs.google.com/document/d/16EOH4sCjJKkgEeGSW4T0kZXWLoove4iBvGZz_hf7xeU/edit) contains unfinished volumes and short side-stories while [our website](http://worldend.github.io/releases.html) has more polished and complete volumes. For example, the Google Docs Translation Index has volume 4 and the Lillia Asplay side story (both unfinished), along with other short bonus stories.

## EPUBs vs. PDFs
### EPUBs
![EPUBs]({{ '/assets/images/epubs.png' | relative_url }}){:.image.image--xl.border.shadow.rounded}
![Kindle EPUBs]({{ '/assets/images/kindle.png' | relative_url }}){:.image.image--xl.border.shadow.rounded}

An EPUB (Electronic Publication) is the most popular file format for e-books and can be displayed using most e-reader programs, such as Calibre or Apple Books. Additionally, they can be sent to be viewed on a Kindle using [Amazon's service](https://www.amazon.com/sendtokindle) or by [using Calibre](https://www.howtogeek.com/539829/how-to-transfer-any-ebook-to-kindle-using-calibre/).

The EPUB version of each volume of *WorldEnd2 (Suka Moka)* is designed to mimic the format of the e-book Yen Press volumes for *WorldEnd (Suka Suka)*.

Unlike PDFs, EPUBs do not preserve the exact formatting. The content will dynamically adjust to your screen size, allowing you to change properties such as font and line spacing.

### PDFs
![PDFs]({{ '/assets/images/pdfs.png' | relative_url }}){:.image.image--xl.border.shadow.rounded}

A PDF (Portable Document Format) is a file format created by Adobe that preserves the formatting of a document across any device.

The PDF version of each volume of *WorldEnd2 (Suka Moka)* is designed to mimic the format of the physical Yen Press volumes for *WorldEnd (Suka Suka)*.

These PDFs are best viewed in a two-page layout, starting with the cover on the right-hand side (not the left). While the viewing experience is ideal in this layout, it's not required. The difference is that images spanning two pages will appear connected if you view them side-by-side. If your PDF reader doesn't support this setup, you can switch readers[^1] or view the left and right sides separately.

[^1]: Adobe Acrobat Reader, Mac Preview, Firefox (PDF.js), SumatraPDF, Foxit, Okular, Evince, and Zathura all support this functionality. While Google Chrome / Chromium can display pages side-by-side, it can't put the cover on the right side. If you prefer using Chrome, you can use the print dialog to save a new PDF without the cover.

## Printing
To print these volumes, you need to understand [bleed](https://printing.umn.edu/tools/what-is-bleed.html) and [gutter](https://www.printivity.com/insights/how-to-design-for-gutter-margins). Since these settings vary depending on the printing service, PDFs must be generated on a case-by-case basis using our [Python scripts](https://github.com/WorldEnd/worldend-formatting).

Since page thickness affects spine width, the cover spread must also be adjusted accordingly. Sample cover spread PSD files are available [here](https://drive.google.com/drive/folders/1YEETsnXm3C5z-xG6uzCyq3WWyyrcIvXz?usp=sharing), but specific measurements will have to be changed. You can generate the required bleed for the front and back cover images by running our Python scripts and navigating to `$OUTPUT_DIR/WorkDir/TeX/Cover/`.

Alternatively, join the [Suka Suka Discord server](https://discord.gg/xXTncqJ) and ask for help. Someone knowledgeable will help adjust the files, provided that you can supply all the necessary specs (bleed, gutter, spine thickness, etc.).
