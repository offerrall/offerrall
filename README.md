# Hi, I'm Offerrall

Self-taught developer since the pandemic. I build libraries that are as fast as I can make them, improving as I learn.

Everything is Python at the surface, but I write CUDA or C underneath when Python alone isn't fast enough.

Currently building a B2B personalized products company. I keep the business-specific 
code private, but share the general-purpose libraries I create along the way.
## Projects

### [PhotoFF](https://github.com/offerrall/photoff) GPU-Accelerated
High-performance CUDA image processing library. Real-time filters, blending, and compositing - all on GPU.

- **Order-of-magnitude faster** than PIL/Pillow (see [benchmarks](https://offerrall.github.io/photoff/benchmarks/))
- **Smart memory management** - allocate once, reuse efficiently
- **Zero GPU-CPU copies** - everything stays on GPU
- Originally built for custom OBS-style rendering engine

⚡ **Next generation in development:** Pure Python.h API (no CFFI), FFmpeg integration, DirectX/OpenGL interop without GPU→CPU copies

[📖 Full Documentation](https://offerrall.github.io/photoff/)

---

### [FuncToWeb](https://github.com/offerrall/FuncToWeb)
Transform any Python function into a complete web app automatically. Just type hints and `run()`.

- **454 tests passing** - battle-tested reliability
- **Zero configuration** - working web app in 30 seconds
- Auto-generated forms, file uploads, dark mode, validation, plots, downloads

```python
from func_to_web import run

def divide(a: int, b: int):
    return a / b

run(divide)  # → http://127.0.0.1:8000
```

[📖 Full Documentation](https://offerrall.github.io/FuncToWeb) • [PyPI Package](https://pypi.org/project/func-to-web/)

---

### [FuncToGUI](https://github.com/offerrall/FuncToGUI)
Turn Python functions into desktop GUI applications. The original version that inspired FuncToWeb.

- Cross-platform (Windows, macOS, Linux)
- Real-time updates or manual execution mode
- Built on Kivy

```python
from functogui import App

def is_even(number: int = 4) -> bool:
    return number % 2 == 0

App(is_even)
```

---

### [pyeasydeploy](https://github.com/offerrall/pyeasydeploy)
Simple Python server deployment toolkit. Deploy to remote servers with just a few lines of code.

- Deploy FastAPI/Flask apps to $5 VPS servers
- Built on Fabric - mix with pure Fabric commands
- Supervisor service management

⚠️ Early stage - APIs may change

---

### [gcode-bounds](https://github.com/offerrall/gcode-bounds)
Fast G-code bounding box generator and framing tool in pure C.

- **26x faster than Python**
- Zero runtime dependencies
- Handles 500MB+ files in seconds
- Universal compatibility (CNC, laser, 3D printer)

---

### [py-telegram-logger](https://github.com/offerrall/py-telegram-logger)
Fast Python logger with optional Telegram notifications. Separate channels for routine logs and critical errors.

- **195k logs/sec (Linux) / 80k logs/sec (Windows)**
- Thread-safe with crash protection

---

### [pygrbl-streamer](https://github.com/offerrall/pygrbl_streamer)
Simple library for controlling CNC machines with GRBL firmware.

- Intelligent buffer management
- Auto-recovery from alarms
- Auto-disconnect detection

### [PyAlias](https://github.com/offerrall/PyAlias-Windows-Alias-Manager)
Fast, persistent command aliases for Windows that behave like real native commands.

- Works in **cmd.exe, PowerShell, Git Bash, MSYS, WSL** — no shell-specific hacks
- Each alias is a tiny **native .exe** that executes instantly
- **3× faster** than using `.bat` script aliases (no cmd.exe startup overhead)
- Persistent across sessions, folders, restarts
- Pure Python setup, but the launcher core is **written in C for speed**

---

## Contributing

Pull requests welcome. I appreciate clear issues, minimal examples, and focused PRs.
