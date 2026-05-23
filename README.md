# Mitaka WASM

Unofficial WebAssembly port of [Mitaka 1.3.1](https://4d2u.nao.ac.jp/mitaka/), a four-dimensional digital universe viewer developed by Tsunehiko Kato and the [4D2U Project](https://4d2u.nao.ac.jp/) at the National Astronomical Observatory of Japan (NAOJ). Built from the MIT-licensed source via Emscripten. **Not affiliated with or endorsed by NAOJ.**

## Usage
Open <https://jsuk.github.io/mitaka-wasm/mitaka.html> or
serve this directory with any HTTP server in your local environment:

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080/mitaka.html> in a modern web browser with WebGL support.

## Files

- `mitaka.html` — Entry point
- `mitaka-<hash>.js` — Emscripten runtime and GL emulation (filename includes git hash for cache-busting)
- `mitaka.wasm` — Compiled application
- `mitaka.data` — Pre-loaded data files (textures, locale, etc.)

## Credits

- **Author**: Tsunehiko Kato
- **Organization**: 4D2U Project, National Astronomical Observatory of Japan
- **Original Version**: 1.3.1 (March 4, 2016)
- **Original Website**: <https://4d2u.nao.ac.jp/mitaka/>

## Support

This is an unofficial port. Please **do not contact NAOJ or the 4D2U Project** about this build — they are not responsible for it and explicitly do not answer source-code inquiries. File issues at <https://github.com/jsuk/mitaka-wasm/issues> instead.

## License

Mitaka is licensed under the MIT License — see [LICENSE](LICENSE).

This build statically links several third-party libraries (libjpeg, libpng, zlib, FreeType, GLEW) and bundles astronomical data files. See [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) for the required attributions.
