# My Libraries
> Python 3.10+ · MIT

### pygrbl — GRBL toolkit
**[pygrbl_build](https://github.com/offerrall/pygrbl_build)** — G-code generator for GRBL diode lasers (raster + SVG), ~350× faster than LaserGRBL.
```
pip install pygrbl-build
```
**[pygrbl_streamer](https://github.com/offerrall/PyGrbl_Streamer)** — streams G-code to GRBL over serial; constant memory, real-time control, auto-reconnect.
```
pip install pygrbl-streamer
```
**[pygrbl_server](https://github.com/offerrall/pygrbl-server)** — FastAPI router and job engine for GRBL over HTTP; one job per port, live status, safety teardown.
```
pip install pygrbl-server
```

### type hints → UI
**[FuncToWeb](https://github.com/offerrall/FuncToWeb)** — turns Python functions into web apps from their type hints. 394★.
```
pip install func-to-web
```
**[PyTypeInput](https://github.com/offerrall/pytypeinput)** — extracts UI metadata from type hints (engine behind FuncToWeb).
```
pip install pytypeinput
```
**[PyTypeInputWeb](https://github.com/offerrall/pytypeinputweb)** — renders validated HTML forms from that metadata (zero JS deps).
```
pip install pytypeinputweb
```
**[pytypehint](https://github.com/offerrall/pytypehint)** — compiles Python type hints into strict, inspectable schemas; the dataclass is the single source of truth. Exact validation, fresh defaults, no coercion. Stdlib only, Python 3.11+.
```
pip install pytypehint
```

### GPU image
**[PyImageCUDA](https://github.com/offerrall/pyimagecuda)** — GPU image compositing; no CUDA Toolkit, ~1 MB, zero-copy interop.
```
pip install pyimagecuda
```
**[PyImageCUDA Studio](https://github.com/offerrall/pyimagecuda-studio)** — node-based compositor with live preview + headless batch.
```
pip install pyimagecuda-studio
```

### deploy
**[pyeasydeploy](https://github.com/offerrall/pyeasydeploy)** — deploy Python apps to Linux servers over SSH in a few lines (on top of Fabric).
```
pip install pyeasydeploy
```

### Windows
**[pywinselect](https://github.com/offerrall/pywinselect)** — detects which files/folders are selected in Explorer or the Desktop, in one line (Windows-only).
```
pip install pywinselect
```
**[windowsctxmenu](https://github.com/offerrall/windowsctxmenu)** — add, remove and block Windows right-click context menu entries from Python; script your menu once, replay it on every PC or reinstall.
```
pip install windowsctxmenu
```

### logging / ops
**[pytelegram_logger](https://github.com/offerrall/py-telegram-logger)** — async logger to file + Telegram; background queues (disk isolated from network), non-blocking with drop counters, zero dependencies.
```
pip install easy-tg-logger
```

### webcams
**[pyezcams](https://github.com/offerrall/pyezcams)** — minimal surveillance node: USB webcams → RTSP/WebRTC via MediaMTX, hardware-encoder auto-detection, native-H.264 passthrough, self-supervising. Linux only.
```
pip install pyezcams
```
