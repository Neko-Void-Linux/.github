# Neko Void Linux (=^･ω･^=)

Welcome to the official Neko Void development organization. We are the team behind the Venezuelan-origin distribution designed to bring the power, lightness, and independence of Void Linux to any user without technical complications. \o/

## About Us (^._.^)ﾉ

Our main focus is to offer the speed of a minimal base system along with a ready-to-use desktop experience. We facilitate the use of a systemd-free environment through graphical installers and native post-installation tools. The system is optimized for various daily workflows, covering (a) gaming [+..••], (b) design, (c) music production ♪, (d) video editing [|>], and (e) office tasks.

## Ecosystem Features (b^_^)b

We work to deliver a highly functional operating system right out of the box. Neko Void includes full Vulkan support with pre-configured Intel and AMD drivers, native PipeWire integration for multimedia workloads, and ready-to-use tools like Flatpak, Octoxbps, and btop. We support architectures with both UEFI and Legacy BIOS systems to ensure maximum hardware compatibility.

## Projects and Collaboration ヽ(´▽`)/

Within this organization, we manage the development environment and foster open-source collaboration. We develop and maintain the core of the distribution, associated launcher tools, and software repositories. We seek to eliminate entry barriers while maintaining the efficiency that characterizes the base system.

## Official Links (ﾉ^ヮ^)ﾉ*:･ﾟ✧

You can find more information, documentation, and access our downloads by visiting our official website at nekovoid.vercel.app or by exploring the pinned repositories on this page. (=^ ◡ ^=)

<img width="130" height="178" alt="Kyoko RENDER" src="https://github.com/user-attachments/assets/324a1096-7447-4781-bad6-5a2c9e56ad3a" />

# KYOUKO LOVE's VOIDLINUX

## Repository Map (🗺️)

```mermaid
graph LR
  NV((Neko Void)) --> Core[Core & Build]
  NV --> HW[Hardware & Kernel]
  NV --> Desktop[Desktop Experience]
  NV --> Tools[Tools & Daemons]
  NV --> Web[Web & Misc]

  Core --> Neko-Void("Neko-Void")
  Core --> repo-neko("repo-neko")
  Core --> rootfs-custom("rootfs-custom")
  Core --> musl-repo("musl-repo")

  click Neko-Void "[https://github.com/Neko-Void-Linux/Neko-Void](https://github.com/Neko-Void-Linux/Neko-Void)"
  click repo-neko "[https://github.com/Neko-Void-Linux/repo-neko](https://github.com/Neko-Void-Linux/repo-neko)"
  click rootfs-custom "[https://github.com/Neko-Void-Linux/rootfs-custom](https://github.com/Neko-Void-Linux/rootfs-custom)"
  click musl-repo "[https://github.com/Neko-Void-Linux/musl-repo](https://github.com/Neko-Void-Linux/musl-repo)"

  HW --> kernel-neko-void("kernel-neko-void")
  HW --> Neko-Kernel-Manager("Neko-Kernel-Manager")
  HW --> nvidia-support("nvidia-support")
  HW --> bluetooth-enabler("bluetooth-enabler")
  HW --> printer-enable("printer-enable")

  click kernel-neko-void "[https://github.com/Neko-Void-Linux/kernel-neko-void](https://github.com/Neko-Void-Linux/kernel-neko-void)"
  click Neko-Kernel-Manager "[https://github.com/Neko-Void-Linux/Neko-Kernel-Manager](https://github.com/Neko-Void-Linux/Neko-Kernel-Manager)"
  click nvidia-support "[https://github.com/Neko-Void-Linux/nvidia-support](https://github.com/Neko-Void-Linux/nvidia-support)"
  click bluetooth-enabler "[https://github.com/Neko-Void-Linux/bluetooth-enabler](https://github.com/Neko-Void-Linux/bluetooth-enabler)"
  click printer-enable "[https://github.com/Neko-Void-Linux/printer-enable](https://github.com/Neko-Void-Linux/printer-enable)"

  Desktop --> Neko-Wizard("Neko-Wizard")
  Desktop --> neko-desktops("neko-desktops")
  Desktop --> neko-backgrounds("neko-backgrounds")

  click Neko-Wizard "[https://github.com/Neko-Void-Linux/Neko-Wizard](https://github.com/Neko-Void-Linux/Neko-Wizard)"
  click neko-desktops "[https://github.com/Neko-Void-Linux/neko-desktops](https://github.com/Neko-Void-Linux/neko-desktops)"
  click neko-backgrounds "[https://github.com/Neko-Void-Linux/neko-backgrounds](https://github.com/Neko-Void-Linux/neko-backgrounds)"

  Tools --> cnr("cnr")
  Tools --> falcond("falcond")
  Tools --> raven-polkit("raven-polkit")
  Tools --> Neko-Update("Neko-Update")
  Tools --> dmemcg-booster-nk("dmemcg-booster-nk")
  Tools --> kyoz("kyoz")

  click cnr "[https://github.com/Neko-Void-Linux/cnr](https://github.com/Neko-Void-Linux/cnr)"
  click falcond "[https://github.com/Neko-Void-Linux/falcond](https://github.com/Neko-Void-Linux/falcond)"
  click raven-polkit "[https://github.com/Neko-Void-Linux/raven-polkit](https://github.com/Neko-Void-Linux/raven-polkit)"
  click Neko-Update "[https://github.com/Neko-Void-Linux/Neko-Update](https://github.com/Neko-Void-Linux/Neko-Update)"
  click dmemcg-booster-nk "[https://github.com/Neko-Void-Linux/dmemcg-booster-nk](https://github.com/Neko-Void-Linux/dmemcg-booster-nk)"
  click kyoz "[https://github.com/Neko-Void-Linux/kyoz](https://github.com/Neko-Void-Linux/kyoz)"

  Web --> nk-web("nk-web")
  Web --> github(".github")
  Web --> demo-repository("demo-repository")

  click nk-web "[https://github.com/Neko-Void-Linux/nk-web](https://github.com/Neko-Void-Linux/nk-web)"
  click github "[https://github.com/Neko-Void-Linux/.github](https://github.com/Neko-Void-Linux/.github)"
  click demo-repository "[https://github.com/Neko-Void-Linux/demo-repository](https://github.com/Neko-Void-Linux/demo-repository)"
