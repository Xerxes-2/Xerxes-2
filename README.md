# Xerxes-2

```rust
struct Hardware {
    cpu: &'static str,
    gpu: &'static str,
    laptops: [&'static str; 2],
    keyboards: [&'static str; 2],
}

struct Software {
    os: [&'static str; 2],
    compositor: &'static str,
    terminals: [&'static str; 2],
    shells: [&'static str; 2],
    editor: &'static str,
}

struct Dev {
    language: &'static str,
    frameworks: [&'static str; 2],
    ci: &'static str,
}

const XERXES: (Hardware, Software, Dev) = (
    Hardware {
        cpu: "AMD Ryzen 9 9950X3D",
        gpu: "AMD Radeon RX 9070 XT",
        laptops: ["MacBook Pro 14 2023", "ThinkPad P14s Gen6 AMD"],
        keyboards: ["NuPhy Air75 V2", "NuPhy Air75 V3"],
    },
    Software {
        os: ["CachyOS", "Arch Linux"],
        compositor: "Niri",
        terminals: ["Ghostty", "Alacritty"],
        shells: ["Fish", "Nushell"],
        editor: "Helix",
    },
    Dev {
        language: "Rust",
        frameworks: ["Tokio", "Axum"],
        ci: "GitHub Actions",
    },
);
```
