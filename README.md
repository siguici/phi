# ⚡ The **Sigui** Programming Language

**SiguiLang** is a modern, high-performance programming language
designed for simplicity, clarity, and expressive power.  
Built with ❤️ in [Vlang](https://vlang.io).

[![Build Status](https://github.com/siguici/siguilang/workflows/CI/badge.svg)](https://github.com/siguici/siguilang/actions)

---

## 🚀 Features

- ✅ Lightweight and fast by design  
- ✅ Optional, strong, or dynamic typing  
- ✅ Clean and minimal syntax  
- ✅ `.sigui` source files  
- ✅ Web and general-purpose scripting  
- ✅ Built-in HTTP server  
- ✅ Native routing, templating, and middleware  

---

## 🌟 Vision

**SiguiLang** redefines how code feels to write and read —
expressive, concise, and powerful.  
Its architecture is designed for **multi-runtime execution**,
paving the way for native support in environments like TypeScript, PHP, and Vlang.

---

## 📦 Installation

> ⚠️ **Requires [Vlang](https://vlang.io)**

```bash
git clone https://github.com/siguici/siguilang
cd siguilang
v src -o sigui
./sigui examples
````

Or build for production:

```bash
v -prod src -o sigui
./sigui examples
```

## 🧪 Quick Start

Create a file `hello.sigui`:

```sigui
string name = scan 'Enter your name: '
if name {
  print 'Hello ', name, '!'
} else {
  print "Hello World!"
}
```

Then run it:

```bash
./sigui run hello
```

---

## 📄 Language Overview

**SiguiLang** combines clarity and expressiveness in a clean syntax:

```sigui
string hello(string name) {
    return 'Hello ', name, '!'
}

print hello("World")
```

### Language Features

- `print`, `echo`
- Functions, conditionals, and loops
- Optional `$` variable prefix
- Inline templates (HTML + SiguiLang)
- Optional and strong typing
- Built-in access to HTTP and environment data

---

## 🔧 Roadmap

- [x] Core parser and runtime
- [x] Built-in HTTP server
- [x] Template rendering
- [ ] Ahead-of-time compilation
- [ ] Optional VM execution model
- [ ] Extended standard library
- [ ] WebSocket support
- [ ] Session & authentication modules
- [ ] CLI tooling for scaffolding and dev mode

---

## 🧠 Philosophy

**SiguiLang** is about writing **natural, structured, and elegant code**.

- No tags
- No semicolons
- Just code that feels right

A minimal language for a maximal experience.

> Designed to be **clear to read**, **pleasant to write**, and **powerful to run**.

---

## 🤝 Contributing

We welcome contributions and ideas!

- 🛠 Fork this repo
- 🔧 Make improvements
- ✅ Test (`v test .`)
- 📬 Open a pull request

---

## 📜 License

[MIT](./LICENSE.md) © [Sigui Kessé Emmanuel](https://github.com/siguici)
