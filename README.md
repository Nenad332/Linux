# Linux notes
<details>
<summary>Philosophy</summary>

|Principle | Description|
| :---: | :---:|
|`Everything is a file`|  hardware devices, processes, network connections are represented as files|
|`Small, single-purpose programs`|
|`Ability to chain programs together to perform complex tasks`|
|`Avoid captive user interfaces`|  Linux is build to work using terminal and gives user greater control over the operating sistem |
|`Configuration data stored in text files`|  /etc/passwd |

</details>
<details>

<summary>Components</summary>

|Components | Description|
| :---: | :---:|
|`Bootloader`|  A piece of code that runs to guide the booting process to start the operating sistem.|
|`OS Kernel`| The kernel is the main component of an operating system. It manages the resources for system's I/O devices at hardware level.  |
|`Daemons`| Scheduling, printing and multimedia  |
|`OS Shell`|  command line |
|`Graphics server`| graphical sub-system |
|`Window Manager`| GUI |
|`Utilities`| Applications |

</details>

<details>

<summary>Linux Architecture</summary>

|Components | Description|
| :---: | :---:|
|`Hardware`| Ram, hard drive, CPU |
|`Kernel`| The core of the Linux operating system whose function is to virtualize and control common computer hardware resources like CPU, allocated memory accessed data and others. |
|`Shell`| A command line interface (CLI) |
|`System Utility`| Makes available to the user all operating system's functionallity. |

</details>

<details>

<summary>File system hierarchy</summary>

|Path | Description|
| :---: | :---:|
|`/`| Root filesystem that contains all the file required to boot the operating system before other filesystems are mounted. |
|`/bin`| Contains essential command binaries. |
|`/boot`| Consists of static bootloader, kernel executable and files required to boot the Linux OS. |
|`/dev`| Contains device files to facilitate access to every hardware device attached to the system. |
|`/etc`|  |

</details>
