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
  'primaryColor': '#0f261a',
  'primaryTextColor': '#bbf7d0',
  'primaryBorderColor': '#22c55e',
  'lineColor': '#166534',
  'secondaryColor': '#14532d',
  'tertiaryColor': '#0f261a',
  'background': '#070f0b',
  'mainBkg': '#0f261a',
  'nodeBorder': '#22c55e',
  'clusterBkg': '#0a1a12',
  'clusterBorder': '#14532d',
  'fontFamily': 'Inter, -apple-system, sans-serif',
  'fontSize': '13px'
}}}%%
flowchart LR

    NekoVoid(("Neko Void"))

    subgraph CORE["Core & Build"]
        direction TB
        Neko-Void["Neko-Void"]
        repo-neko["repo-neko"]
        rootfs-custom["rootfs-custom"]
        musl-repo["musl-repo"]
    end

    subgraph HW["Hardware & Kernel"]
        direction TB
        kernel-neko-void["kernel-neko-void"]
        Neko-Kernel-Manager["Neko-Kernel-Manager"]
        nvidia-support["nvidia-support"]
        bluetooth-enabler["bluetooth-enabler"]
        printer-enable["printer-enable"]
    end

    subgraph DESKTOP["Desktop Experience"]
        direction TB
        Neko-Wizard["Neko-Wizard"]
        neko-desktops["neko-desktops"]
        neko-backgrounds["neko-backgrounds"]
    end

    subgraph TOOLS["Tools & Daemons"]
        direction TB
        cnr["cnr"]
        falcond["falcond"]
        raven-polkit["raven-polkit"]
        Neko-Update["Neko-Update"]
        dmemcg-booster-nk["dmemcg-booster-nk"]
        kyoz["kyoz"]
    end

    subgraph WEB["Web & Misc"]
        direction TB
        nk-web["nk-web"]
        github[".github"]
        demo-repository["demo-repository"]
    end

    NekoVoid -->|build| CORE
    NekoVoid -->|drivers| HW
    NekoVoid -->|ui| DESKTOP
    NekoVoid -->|utils| TOOLS
    NekoVoid -->|docs| WEB

    classDef core fill:#0f261a,stroke:#22c55e,stroke-width:1px,color:#bbf7d0
    classDef hw fill:#0a1f1a,stroke:#10b981,stroke-width:1px,color:#a7f3d0
    classDef desktop fill:#0f1f0f,stroke:#84cc16,stroke-width:1px,color:#d9f99d
    classDef tools fill:#0a1a1a,stroke:#14b8a6,stroke-width:1px,color:#99f6e4
    classDef web fill:#141f0a,stroke:#a3e635,stroke-width:1px,color:#ecfccb
    classDef center fill:#14532d,stroke:#4ade80,stroke-width:2px,color:#dcfce7,font-weight:bold

    class Neko-Void,repo-neko,rootfs-custom,musl-repo core
    class kernel-neko-void,Neko-Kernel-Manager,nvidia-support,bluetooth-enabler,printer-enable hw
    class Neko-Wizard,neko-desktops,neko-backgrounds desktop
    class cnr,falcond,raven-polkit,Neko-Update,dmemcg-booster-nk,kyoz tools
    class nk-web,github,demo-repository web
    class NekoVoid center

    linkStyle 0 stroke:#22c55e,stroke-width:2px
    linkStyle 1 stroke:#10b981,stroke-width:2px
    linkStyle 2 stroke:#84cc16,stroke-width:2px
    linkStyle 3 stroke:#14b8a6,stroke-width:2px
    linkStyle 4 stroke:#a3e635,stroke-width:2px
```
