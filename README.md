<div align="center">
  <h1>🎲 Dioxus Primitives 🧱</h1>
  <p><strong>Accessible, unstyled, foundational components for Dioxus.</strong></p>
</div>

<div align="center">
  <!-- Crates version -->
  <a href="https://crates.io/crates/dioxus-primitives">
    <img src="https://img.shields.io/crates/v/dioxus-primitives.svg?style=flat-square"
    alt="Crates.io version" />
  </a>
  <!-- Downloads -->
  <a href="https://crates.io/crates/dioxus-primitives">
    <img src="https://img.shields.io/crates/d/dioxus-primitives.svg?style=flat-square"
      alt="Download" />
  </a>
  <!-- docs -->
  <a href="https://docs.rs/dioxus-primitives">
    <img src="https://img.shields.io/badge/docs-latest-blue.svg?style=flat-square"
      alt="docs.rs docs" />
  </a>
</div>

---

<br/>

Dioxus primitives is an ARIA-accessible, unstyled, foundational component library for Dioxus based on Radix Primitives. We bring the logic, you bring the styling.

Building styled and more featured component libraries on top of Dioxus Primitives is encouraged!

## Here's what we have.

We're still in the early days - Many components are still being created and stabilized.

28/28

- [x] Accordion
- [x] Alert Dialog
- [x] Aspect Ratio
- [x] Avatar
- [x] Calendar
- [x] Checkbox
- [x] Collapsible
- [x] Context Menu
- [x] Dialog
- [x] Dropdown Menu
- [x] Hover Card
- [x] Label
- [x] Menubar
- [x] Navigation Menu
- [x] Popover
- [x] Progress
- [x] Radio Group
- [x] Scroll Area
- [x] Select
- [x] Separator
- [x] Slider
- [x] Switch
- [x] Tabs
- [x] Toast
- [x] Toggle
- [x] Toggle Group
- [x] Toolbar
- [x] Tooltip

## Running the preview.

You can run the `preview` app with:

```
cargo run -p preview --features desktop
```

or for the web build

```
cargo binstall dioxus-cli -y --force --version 0.7.0-alpha.3
dx run -p preview --platform web
```

## License

This project is dual licensed under the [MIT](./LICENSE-MIT) and [Apache 2.0](./LICENSE-APACHE) licenses.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in this repository, by you, shall be licensed as MIT or Apache 2.0, without any additional terms or conditions.
