# Third-Party Licenses

This WebAssembly build of Mitaka statically links several open-source libraries and bundles data assets that carry their own copyright notices. Mitaka itself is MIT-licensed (see [LICENSE](LICENSE)).

## Bundled astronomical data and imagery

The full list of star catalogs, ephemerides, image sources, and 3D models bundled in `mitaka.data` is shown by Mitaka's built-in credit roll (accessible from the application's menu). It includes — among others — the Hipparcos and Tycho Catalogues (ESA), the Bright Star Catalogue (Hoffleit), the Tully Nearby Galaxies Catalogue, SDSS DR4, NGC 2000.0, the Yale Constellation Boundary Data, JPL HORIZONS ephemerides, NASA Blue Marble, MOLA data, 2MASS, Axel Mellinger's Milky Way panorama, ESA/Planck imagery, and 3D models / illustrations contributed by Bjørn Jónsson, James Hastings-Trew, David Seal, Hatsuki Shima, Syōta Hirasawa, and Yuki Nakamura. All credits as embedded by the original authors are preserved in this build.

## Statically-linked libraries

### zlib
Copyright (C) 1995-2017 Jean-loup Gailly and Mark Adler. Licensed under the [zlib License](https://www.zlib.net/zlib_license.html). Requires preservation of the copyright notice; no attribution required in binary distributions, but included here as a courtesy.

### libpng
Copyright (c) 1995-2024 The PNG Reference Library Authors. Licensed under the [libpng license](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt) (a permissive license similar to zlib).

### libjpeg (Independent JPEG Group)
This software is based in part on the work of the Independent JPEG Group. Licensed under the [IJG License](https://jpegclub.org/reference/). The IJG license requires that documentation accompanying a product using libjpeg include the acknowledgement above.

### FreeType
Portions of this software are copyright © The FreeType Project (<https://www.freetype.org>). All rights reserved. Used under the [FreeType License (FTL)](https://gitlab.freedesktop.org/freetype/freetype/-/blob/master/docs/FTL.TXT), a BSD-style license with a credit clause.

### GLEW — The OpenGL Extension Wrangler Library
Copyright (C) 2002-2007 Milan Ikits, Marcelo E. Magallon, and Lev Povalahev. Licensed under the [Modified BSD License, the Mesa 3-D License (MIT), and the Khronos License (MIT)](http://glew.sourceforge.net/glew.txt). Requires preservation of the copyright and license notices.

## Bundled fonts

### DejaVu Fonts
Based on Bitstream Vera Fonts. © 2003 Bitstream, Inc. All Rights Reserved. DejaVu changes © 2006 Tavmjong Bah. Released under the [DejaVu Fonts License](https://dejavu-fonts.github.io/License.html) (a permissive license derived from the Bitstream Vera license). Bitstream Vera is a trademark of Bitstream, Inc.

---

If you believe any attribution is missing or incorrect, please open an issue at <https://github.com/jsuk/mitaka-wasm/issues>.
