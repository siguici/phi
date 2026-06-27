# Phi <a href="https://phici.github.io/phi" title="Phi"><img src="https://github.com/phici/art/blob/HEAD/phi-logo.svg?raw=true" alt="φ" height="24"/></a>

**Phi** is a modern, high-performance programming language
designed for simplicity, clarity, and expressive power.  
Built with ❤️ in [Vlang](https://vlang.io).

[![Build Status](https://github.com/phici/philang/workflows/CI/badge.svg)](https://github.com/phici/philang/actions)

---

## 🚀 Features

- ✅ Lightweight and fast by design  
- ✅ Optional, strong, or dynamic typing  
- ✅ Clean and minimal syntax  
- ✅ `.phi` source files  
- ✅ Web and general-purpose scripting  
- ✅ Built-in HTTP server  
- ✅ Native routing, templating, and middleware  

---

## 🌟 Vision

**Phi** redefines how code feels to write and read —
expressive, concise, and powerful.  
Its architecture is designed for **multi-runtime execution**,
paving the way for native support in environments like TypeScript, PHP, and Vlang.

---

## 📦 Installation

> ⚠️ **Requires [Vlang](https://vlang.io)**

```bash
git clone https://github.com/phici/philang
cd philang
v src -o phi
./phi examples
````

Or build for production:

```bash
v -prod src -o phi
./phi examples
```

## 🧪 Quick Start

Create a file `hello.phi`:

```phi
string name = scan 'Enter your name: '
if name {
  print 'Hello ', name, '!'
} else {
  print "Hello World!"
}
```

Then run it:

```bash
./phi run hello
```

---

## 📄 Language Overview

**Phi** combines clarity and expressiveness in a clean syntax:

```phi
string hello(string name) {
    return 'Hello ', name, '!'
}

print hello("World")
```

### Language Features

- `print`, `echo`
- Functions, conditionals, and loops
- Optional `$` variable prefix
- Inline templates (HTML + Phi)
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

**Phi** is about writing **natural, structured, and elegant code**.

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

[MIT](./LICENSE.md) © [Sigui Kessé Emmanuel](https://github.com/phici)
