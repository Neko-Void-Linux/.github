# Neko Void Linux (=^･ω･^=)

Welcome to the official Neko Void development organization. We are the team behind the Venezuelan-origin distribution designed to bring the power, lightness, and independence of Void Linux to any user without technical complications. \o/

## About Us (^._.^)ﾉ

Our main focus is to offer the speed of a minimal base system along with a ready-to-use desktop experience. We facilitate the use of a systemd-free environment through graphical installers and native post-installation tools. The system is optimized for various daily workflows, covering (a) gaming [+..••], (b) design, (c) music production ♪, (d) video editing [|>], and (e) office tasks.

## Ecosystem Features (b^_^)b

We work to deliver a highly functional operating system right out of the box. Neko Void includes full Vulkan support with pre-configured Intel and AMD drivers, native PipeWire integration for multimedia workloads, and ready-to-use tools like iruka-xbps, Neko-Kernel-Manager, Vouru, Falcond, and btop. We support architectures with both UEFI and Legacy BIOS systems to ensure maximum hardware compatibility.

## Projects and Collaboration ヽ(´▽`)/

Within this organization, we manage the development environment and foster open-source collaboration. We develop and maintain the core of the distribution, associated launcher tools, and software repositories. We seek to eliminate entry barriers while maintaining the efficiency that characterizes the base system.

## Official Links (ﾉ^ヮ^)ﾉ*:･ﾟ✧

You can find more information, documentation, and access our downloads by visiting our official website at nekovoid.vercel.app or by exploring the pinned repositories on this page. (=^ ◡ ^=)

<img width="130" height="178" alt="Kyoko RENDER" src="https://github.com/user-attachments/assets/324a1096-7447-4781-bad6-5a2c9e56ad3a" />

# KYOUKO LOVE's VOIDLINUX

## Repository Map UwU

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {
  'primaryColor': '#14532d',
  'primaryTextColor': '#dcfce7',
  'primaryBorderColor': '#22c55e',
  'lineColor': '#166534',
  'secondaryColor': '#0f261a',
  'tertiaryColor': '#0a1a12',
  'background': '#050d09',
  'mainBkg': '#14532d',
  'nodeBorder': '#22c55e',
  'clusterBkg': '#0a1a12',
  'clusterBorder': '#166534',
  'fontFamily': 'Inter, -apple-system, sans-serif',
  'fontSize': '12px'
}}}%%
flowchart LR

    NV(("Neko Void"))

    NV --> C(["Core & Build"])
    NV --> H(["Hardware & Kernel"])
    NV --> D(["Desktop Experience"])
    NV --> T(["Tools & Daemons"])
    NV --> W(["Web & Misc"])

    C --> C1["Neko-Void"]
    C --> C2["repo-neko"]
    C --> C3["rootfs-custom"]
    C --> C4["musl-repo"]

    H --> H1["kernel-neko-void"]
    H --> H2["Neko-Kernel-Manager"]
    H --> H3["nvidia-support"]
    H --> H4["bluetooth-enabler"]
    H --> H5["printer-enable"]

    D --> D1["Neko-Wizard"]
    D --> D2["neko-desktops"]
    D --> D3["neko-backgrounds"]

    T --> T1["cnr"]
    T --> T2["falcond"]
    T --> T3["raven-polkit"]
    T --> T4["Neko-Update"]
    T --> T5["dmemcg-booster-nk"]
    T --> T6["kyoz"]

    W --> W1["nk-web"]
    W --> W2[".github"]
    W --> W3["demo-repository"]

    classDef center fill:#166534,stroke:#4ade80,stroke-width:2px,color:#f0fdf4,font-weight:bold
    classDef cat fill:#14532d,stroke:#22c55e,stroke-width:1px,color:#dcfce7,font-weight:bold
    classDef repo fill:#0a1f15,stroke:#15803d,stroke-width:1px,color:#bbf7d0

    class NV center
    class C,H,D,T,W cat
    class C1,C2,C3,C4,H1,H2,H3,H4,H5,D1,D2,D3,T1,T2,T3,T4,T5,T6,W1,W2,W3 repo
```
