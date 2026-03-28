# Mitaka WASM

Pre-built WebAssembly distribution of [Mitaka](https://github.com/jsuk/mitaka), a four-dimensional digital universe viewer developed by Tsunehiko Kato and the [4D2U Project](https://4d2u.nao.ac.jp/) at the National Astronomical Observatory of Japan (NAOJ).

## Usage

Serve this directory with any HTTP server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080/mitaka.html` in a modern web browser with WebGL support.

## Files

- `mitaka.html` — Entry point
- `mitaka.js` — Emscripten runtime and GL emulation
- `mitaka.wasm` — Compiled application
- `mitaka.data` — Pre-loaded data files (textures, locale, etc.)

## Credits

- **Author**: Tsunehiko Kato
- **Organization**: 4D2U Project, National Astronomical Observatory of Japan
- **Original Version**: 1.3.1 (March 4, 2016)
- **Original Website**: https://4d2u.nao.ac.jp/mitaka/

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
