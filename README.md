
## Hi, I am `sudo_free` (or `iamhyc`)

> !!! LOOKING FOR JOB OPPORTUNITIES !!!
> My CV link is on the left column if you are interested.

I am currently working on [Overleaf Workshop](https://github.com/iamhyc/Overleaf-Workshop/), which allows you to open Overleaf projects in VS Code with full collaboration support. 

[![Github Stats](https://github-readme-stats.vercel.app/api?username=iamhyc&bg_color=0D1117&text_color=FFFFFF&count_private=true&show_icons=true&hide_border=true)](https://github.com/iamhyc)

----

### My Skills

An amazing project, [Virtual Domain Manager (VDM)](https://github.com/VDM-Maintainer-Group/virtual-domain-manager), well summarizes my software engineering skills, including but not limited to:

- **Homebrew RPC framework**: The source code is encapsuled at build time with [function wrapper](https://github.com/VDM-Maintainer-Group/vdm-capability-library/tree/main/__wrapper__) for `CString` signature, and then loaded and called at runtime via [FFI Manager](https://github.com/VDM-Maintainer-Group/virtual-domain-manager/tree/master/daemon/serde-ipc).

- **Plugin framework**: The plugins for VDM are called via [D-Bus](https://www.freedesktop.org/wiki/Software/dbus/) with [specific interface definition](https://github.com/VDM-Maintainer-Group/virtual-domain-manager/blob/master/interface/org.vdm-compatible.src.xml).

- **Linux kernel rootkit**: One unique and efficient solution to provide in-kernel `inotify_group` reverse lookup. Both `inotify_add_watch` and `inotify_rm_watch` [syscalls](https://man7.org/linux/man-pages/man2/syscalls.2.html) are hooked via [`kprobe` mechanism](https://docs.kernel.org/trace/kprobes.html) to maintain the reverse lookup table with [radix tree](https://lwn.net/Articles/175432/). The userspace lookup is queried via [custom Netlink protocol](https://github.com/VDM-Maintainer-Group/vdm-capability-library/tree/main/inotify-lookup/inotify-lookup-py).

- **Front-end developing**: A [Manifest V2](https://developer.chrome.com/docs/extensions/mv2) browser extension to get browser tabs and then pass to local connector via [Native Messaging](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Native_messaging) with AES encryption.

- **X11 Window Management**, **Python Packaging**, **PyQt for GUI**, and etc.

### My Interests

I am currently a freelance researcher and developer, who is interested in the following fields:

**Researches**: 1) distributed-native network, 2) pre-trained transformer, 3) text-instructed 3D generation ([LRM](https://arxiv.org/abs/2311.04400) is interesting).

**Development**: 1) RetroArch for OpenHarmony, 2) [Overleaf Workshop](https://github.com/iamhyc/Overleaf-Workshop), 3) [VDM](https://github.com/VDM-Maintainer-Group).
