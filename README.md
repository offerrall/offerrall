# Hi, I'm Offerrall

Self-taught developer since 2020. I enjoy building tools to solve my own problems and sharing them here in case they help others.

I write mostly in Python, dipping into C or CUDA only when I really need the extra speed.

Currently building a personalized products business. I open-source the general tools I create along the way.
## Projects

**Contact:** [@Offedev](https://twitter.com/Offedev) on Twitter

### [PyImageCUDA](https://github.com/offerrall/pyimagecuda)
**GPU-accelerated image compositing for Python.**

- **Zero Dependencies:** Works with standard NVIDIA drivers (No CUDA Toolkit/Visual Studio required).
- **Studio Quality:** 32-bit float precision throughout the pipeline.
- **Massive Speedups:** 10-200x faster than CPU for blur, blends, and transforms.
- **Smart Memory:** Buffer reuse for zero-allocation video/batch processing.
- **Rich Features** - +40 operations (gradients, blend modes, effects...)

[Full Documentation](https://offerrall.github.io/pyimagecuda/)

---

### [PyImageCUDA Studio](https://github.com/offerrall/pyimagecuda-studio)
**Visual node editor built on PyImageCUDA with headless automation.**
- **40+ GPU nodes** - Design image pipelines visually with real-time preview
- **Python automation** - Export templates and generate thousands of variations
- **Global variables** - Parameterize templates for batch processing
- **CUDA-OpenGL preview** - Zero-copy GPU rendering

---

### [FuncToWeb](https://github.com/offerrall/FuncToWeb) +340 stars
Transform any Python function into a complete web app automatically. Just type hints and `run()`.

- **454 tests passing** - battle-tested reliability
- **Zero configuration** - working web app in 30 seconds
- Auto-generated forms, file uploads, dark mode, validation, plots, downloads...

```python
from func_to_web import run

def divide(a: int, b: int):
    return a / b

run(divide)  # → http://127.0.0.1:8000
```

[Full Documentation](https://offerrall.github.io/FuncToWeb)

---

### [FuncToGUI](https://github.com/offerrall/FuncToGUI) 90 stars
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

---

### [pygrbl-streamer](https://github.com/offerrall/pygrbl_streamer)
Simple library for controlling CNC machines with GRBL firmware.

- Intelligent buffer management
- Auto-recovery from alarms
- Auto-disconnect detection

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

### [PyAlias](https://github.com/offerrall/PyAlias-Windows-Alias-Manager)
PyAlias
Command aliases for Windows that actually work like native commands.
- 21x faster than .bat files
- Works in any terminal
- Zero startup overhead

---

### [pywinselect](https://github.com/offerrall/pywinselect)
Get selected files and folders in Windows. One line of code.

- **Safe by design** - read-only Windows Shell COM APIs, no keyboard simulation
- **Works everywhere** - File Explorer and Desktop
- **Zero side effects** - no clipboard modifications or system state changes

---

## Contributing

Pull requests welcome. I appreciate clear issues, minimal examples, and focused PRs.
