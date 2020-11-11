<p align="center">
  <a href="https://github.com/AdrianGjerstad/linux-syscall-info">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Tux.png" width="80" alt="Tux the Linux Mascot" title="Tux, The Linux Mascot"/><br/>
  </a>
  <i>(Original by <a href="mailto:lewing@isc.tamu.edu">lewing@isc.tamu.edu &lt;Larry Ewing&gt;</a> and <a href="https://en.wikipedia.org/wiki/GIMP">The GIMP</a>)</i>
  
  <h3 align="center">Linux System Call Information</h3>
  
  <p align="center">
    Explanatory linux system call documentation for assembly users.
    <br/>
    <a href="https://adriangjerstad.github.io/linux-syscall-info"><strong>Explore »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/AdrianGjerstad/linux-syscall-info/issues">Issues</a>
    &middot;
    <a href="#contributors-">Contributors</a>
    <br/>
    <br/>
    <a href="https://github.com/AdrianGjerstad/linux-syscall-info/network/members">
    <img src="https://img.shields.io/github/forks/AdrianGjerstad/linux-syscall-info.svg?style=flat-square"></a>
    <a href="https://github.com/AdrianGjerstad/linux-syscall-info/stargazers">
    <img src="https://img.shields.io/github/stars/AdrianGjerstad/linux-syscall-info.svg?style=flat-square"></a>
    <a href="https://github.com/AdrianGjerstad/linux-syscall-info/issues">
    <img src="https://img.shields.io/github/issues/AdrianGjerstad/linux-syscall-info.svg?style=flat-square"></a>
    <a href="https://github.com/AdrianGjerstad/linux-syscall-info/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/AdrianGjerstad/linux-syscall-info?style=flat-square"></a>
    <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
    <a href="#contributors-">
    <img src="https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square" alt="All Contributors"></a>
    <!-- ALL-CONTRIBUTORS-BADGE:END -->
  </p>
</p>

## Table of Contents

- [About Project](#about-project)
- [Usage](#usage)
- [Contributors](#contributors-)

## About Project

Linux system calls are core functionality to the Linux kernel itself. Without it, you would be able to do next to nothing. You could manipulate registers or the stack, do math, etc. That would be pretty limiting, seeing as you need to use the kernel to output results. System calls can be used for a variety of different things, and the documentation on them is ... lacking.

This project is here to change that. We want to have comprehensive documentation for every last system call in the latest kernel, so that you don't have to spend hours determining how things work, and you can get back to your original goal.

## Usage

Besides making learning about system calls as easy as possible, we want to make these docs as easy to navigate as possible. And to do that, we have adopted the following strategy.

**System call** documentation can be found starting with the URI `syscall/`. So if we wanted to learn about building a server in assembly, we could start with [/syscall/sys_bind](https://adriangjerstad.github.io/linux-syscall-info/syscall/sys_bind). You can also find an index of them at [/syscall](https://adriangjerstad.github.io/linux-syscall-info/syscall).

**Error number** documentation can be found starting with the URI `errno/`. So if we wanted to learn why we keep receiving trouble with `-EBADF`, we could just go to [/errno/EBADF](https://adriangjerstad.github.io/linux-syscall-info/errno/EBADF) (It means there's no file open with that file descriptor). You can also find an index of them at [/errno](https://adriangjerstad.github.io/linux-syscall-info/errno).

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/AdrianGjerstad"><img src="https://avatars2.githubusercontent.com/u/48812634?v=4" width="100px;" alt=""/><br /><sub><b>Adrian</b></sub></a><br /><a href="#content-adriangjerstad" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

