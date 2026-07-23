# Xerxes-2

[![wakatime](https://wakatime.com/badge/user/018c22e2-3a16-4515-89d4-56797f9e644d.svg)](https://wakatime.com/@018c22e2-3a16-4515-89d4-56797f9e644d)

```rust
struct Hardware {
    cpu: &'static str,
    gpu: &'static str,
    laptops: [&'static str; 1],
    keyboards: [&'static str; 1],
}

struct Software {
    os: [&'static str; 2],
    compositor: &'static str,
    terminals: [&'static str; 2],
    shells: [&'static str; 2],
    editor: &'static str,
}

const XERXES_2: (Hardware, Software) = (
    Hardware {
        cpu: "AMD Ryzen 9 9950X3D",
        gpu: "AMD Radeon RX 9070 XT",
        laptops: ["MacBook Pro 14 2023"],
        keyboards: ["NuPhy Air75 V2"],
    },
    Software {
        os: ["CachyOS", "Asahi Fedora", "macOS"],
        compositor: "Niri",
        terminals: ["Ghostty", "Kitty"],
        shells: ["Fish", "Nushell"],
        editor: "Helix",
    },
);
```
