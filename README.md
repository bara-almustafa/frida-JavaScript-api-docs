# 🕵️ Frida JavaScript API Docs Summary

> A clean, searchable, offline-ready HTML reference table for the **Frida JavaScript API** — built for reverse engineers, mobile security researchers, and anyone who instruments processes with Frida.

<div align="center">

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-cc2200?style=for-the-badge&logo=html5&logoColor=white)
![Frida](https://img.shields.io/badge/Frida-JS%20API-cc2200?style=for-the-badge&logo=frida&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-cc2200?style=for-the-badge)
![Author](https://img.shields.io/badge/By-0xCyberSolider-cc2200?style=for-the-badge)

</div>

---

## 📸 Preview

```
┌──────────────────────────────────────────────────────────────────────────────────┐
│         Frida JavaScript API Docs Summary — By 0xCyberSolider                   │
├────────────────────────────┬──────────────┬────────────────────┬─────────────────┤
│ Category                   │ Section      │ Property / Method  │ Explanation     │
├────────────────────────────┼──────────────┼────────────────────┼─────────────────┤
│ Runtime information        │ Frida        │ Frida.version      │ Current version │
│                            │ Script       │ Script.evaluate()  │ Eval JS string  │
├────────────────────────────┼──────────────┼────────────────────┼─────────────────┤
│ Process / Thread / Memory  │ Process      │ Process.id         │ PID as number   │
│                            │ Memory       │ Memory.scan()      │ Scan for bytes  │
├────────────────────────────┼──────────────┼────────────────────┼─────────────────┤
│ Instrumentation            │ Interceptor  │ Interceptor.attach │ Hook functions  │
│                            │ Stalker      │ Stalker.follow()   │ Trace execution │
└────────────────────────────┴──────────────┴────────────────────┴─────────────────┘
```

---

## ✨ Features

- 🔴 **Dark terminal aesthetic** — red-on-black hacker theme with scanline overlay and glow effects
- 🔍 **Live search** — filter across category, section, method name, and description instantly
- 📂 **Category filter** — jump to any API group with a dropdown
- 📋 **130+ entries** covering every section of the official Frida JS API
- 📴 **Fully offline** — single `.html` file, zero dependencies, no CDN calls
- 💻 **No install needed** — just open in your browser

---

## 🗂️ API Categories Covered

| Category | Sections |
|---|---|
| **Runtime information** | Frida, Script |
| **Process / Thread / Module / Memory** | Process, Thread, Module, ModuleMap, Memory, MemoryAccessMonitor, CModule, RustModule, ApiResolver, DebugSymbol, Kernel |
| **Data Types / Function / Callback** | Int64, UInt64, NativePointer, ArrayBuffer, NativeFunction, NativeCallback, SystemFunction |
| **Network** | Socket, SocketListener, SocketConnection |
| **File and Stream** | File, IOStream, InputStream, OutputStream, UnixInputStream, UnixOutputStream, Win32InputStream, Win32OutputStream |
| **Database** | SqliteDatabase, SqliteStatement |
| **Instrumentation** | Interceptor, Stalker, ObjC, Java |
| **CPU Instruction** | Instruction, X86Writer, X86Relocator, ArmWriter, ArmRelocator, ThumbWriter, ThumbRelocator, Arm64Writer, Arm64Relocator, MipsWriter, MipsRelocator |
| **Other** | Console, Hexdump, send/recv, rpc.exports, Timing, Worker, Cloak, Profiler, Samplers |

---

## 🚀 Usage

No installation required. Just:

1. **Download** `index.html`
2. **Open** it in any modern browser
3. **Search** or **filter** to find what you need

```bash
# Clone the repo
git clone https://github.com/bara-almustafa/frida-JavaScript-api-docs.git

# Open the file
open frida-api-docs.html       # macOS
xdg-open frida-api-docs.html  # Linux
start frida-api-docs.html      # Windows
```

---

## 🔎 How to Use the Search

| Action | How |
|---|---|
| Search by method name | Type `Memory.scan` in the search bar |
| Search by keyword | Type `hook`, `thread`, `scan`, etc. |
| Filter by category | Use the category dropdown |
| Reset | Clear the search box |

---

## 📖 Source

This reference is based on the official [Frida JavaScript API documentation](https://frida.re/docs/javascript-api/).  
All credit for the API design goes to the [Frida project](https://frida.re) and its contributors.

This table was built as a **quick-reference companion** — not a replacement for the full docs.

---

## 👤 Author

**0xCyberSolider**  
Security researcher & reverse engineering enthusiast.

- Follow for more tools and writeups

---

## 📄 License

```
MIT License — free to use, modify, and share.
Just keep the author credit in the file.
```

---

<div align="center">
  <sub>Built with ❤️ and a lot of <code>Interceptor.attach()</code> calls</sub>
</div>
