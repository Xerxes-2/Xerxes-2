# Xerxes-2

[![wakatime](https://wakatime.com/badge/user/018c22e2-3a16-4515-89d4-56797f9e644d.svg)](https://wakatime.com/@018c22e2-3a16-4515-89d4-56797f9e644d)

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

const XERXES_2: (Hardware, Software, Dev) = (
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
