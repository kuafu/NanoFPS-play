# Third-Party Software Notices

League of frontend (《前台英雄传说》) incorporates or builds upon the following third-party open-source packages. All runtime production code in `dist/` is built strictly from modular TypeScript sources plus the `three` runtime dependency listed below (with zero CDN or external runtime asset fetches).

## Runtime Dependency

### three (`0.180.0`)
- Homepage / Repository: https://github.com/mrdoob/three.js/tree/r180
- License file: https://github.com/mrdoob/three.js/blob/r180/LICENSE

```text
The MIT License

Copyright © 2010-2025 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## Development & Test Toolchain (`devDependencies`, not shipped in `dist/`)

- `vite` (`8.3.8`) — MIT License
- `typescript` (`5.9.3`) — Apache-2.0 License
- `vitest` (`5.1.0`) — MIT License
- `@playwright/test` (`1.65.0`) — Apache-2.0 License
- `@types/three` (`0.180.0`) — MIT License
- `@types/node` (`24.0.0`) — MIT License
