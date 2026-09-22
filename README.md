# Java Virtual Machine (JVM) & Java Features Presentation

An interactive, zero-dependency, cinematic HTML presentation on **Java Virtual Machine (JVM) Architecture and Java Features** built with Three.js, GSAP, and responsive fluid layouts.

## 🚀 Features
- **Cinematic Bytecode Space Environment**: Real-time Three.js ambient particle space system with floating wireframe geometric meshes and dynamic camera sway.
- **Fluid & Ultrawide Responsive Engine**: Supports all aspect ratios from laptop (1366×768) to 21:9 / 32:9 ultrawide displays with `clamp()` tokens and responsive CSS Grid/Flexbox layouts.
- **Visual Design Parity**: Glassmorphism (`backdrop-filter: blur(28px)`), radial gradient depth, SVG film grain noise overlay, and drifting ambient glow orbs.
- **Interactive Technical Simulations**:
  1. **Title & Speaker Metadata**: K. Agasthya Reddy | 25B81A6768 | CSD-B
  2. **Core Foundation & Philosophy**: `javac` compiler pipeline to universal `.class` bytecode (`0xCAFEBABE`)
  3. **Architectural Pillars**: Platform independence, automatic memory management, HotSpot JIT compilation, and security sandboxing
  4. **Complete Subsystem Map**: Individually boxed Class Loader, Runtime Memory Areas (Heap, Metaspace, Stacks, PC Registers, Native Stacks), Execution Engine, and JNI
  5. **Class Loader in Action**: Parent-first delegation hierarchy (Bootstrap → Platform → App) and 3-stage lifecycle (Loading, Linking, Initialization)
  6. **Runtime Memory & Thread Isolation**: Thread-private stacks & PC registers vs thread-shared Heap & Metaspace
  7. **Stack Frames vs Heap Allocation**: Live execution trace of method calls, primitive local variables, and reference pointers to heap objects
  8. **PC Register & Bytecode Execution Loop**: Opcode execution tracking (`iadd`), operand stack push/pop evaluation, and instruction pointer offsets
  9. **Execution Engine & Tiered Compilation**: Fast Interpreter startup → HotSpot Profiler invocation thresholds → C1/C2 JIT native x86_64/ARM64 generation
  10. **Garbage Collection & Reachability Analysis**: Root tracing from thread stacks/statics, live object graphs, and sweep/reclamation of cyclic unreachables
  11. **Key Architectural Takeaways & Summary**: Summary pills and closing presenter attribution
- **Interactive Navigation**:
  - `→` / `Space` / `Page Down` / `↓`: Next Slide
  - `←` / `Page Up` / `↑`: Previous Slide
  - `Home` / `End`: Jump to Start / Finish
  - `F`: Toggle Fullscreen Mode
- **Zero-Dependency Architecture**: Standalone, portable web presentation in a single HTML file using CDN-loaded Three.js and GSAP.

## 💻 Local Usage
Simply open `index.html` in any modern web browser:
```bash
# Linux
xdg-open index.html

# macOS
open index.html

# Windows
start index.html
```

---
*Academic Presentation: Computer Science & Engineering (CSD-B)*  
*Topic: Java Virtual Machine & Features of Java*  
*Presenter: K. Agasthya Reddy (25B81A6768)*
