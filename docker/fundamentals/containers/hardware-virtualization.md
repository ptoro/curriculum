---
author: nem035
aspects:
  - introduction
category: must-know
type: normal
links:
  - '[Virtualization](https://en.wikipedia.org/wiki/Virtualization){documentation}'
  - '[Reasons to start using a VM](https://www.makeuseof.com/tag/reasons-start-using-virtual-machine/){article}'
---

# Virtualization

---
## Content

Historically, software applications were limited to running only on specific physical devices. This meant that there was an unavoidable hardware requirement during development as well as during deployment of software.

Supporting and maintaining various physical devices was very expensive.

Virtualization was invented as a response to this, enabling software to emulate a particular hardware system. This allowed us to run applications with different hardware requirements on the same physical machine, significantly lowering costs.

The virutalization software emulating the functionality of a physical computer is called A Virtual Machine (VM). It is an (operating system or application) environment that is installed on software and imitates dedicated hardware, giving the user the same experience as they would have on the actual hardware.

From the user's perspective, the virtual machine is a real, physical computer.

Within each virtual machine we usually run a unique guest operating system. For example, if we wanted to run Windows on a MacOS machine, we would do it via virtualization software.

A VM includes a full copy of an operating system, the application, necessary binaries and libraries.

We could even run multiple VMs on the same physical device, each with a different operating system, significantly reducing the necessity for a lot of hardware.

Virtualization provided an abstraction on top of hardware that allowed development, execution, and deployment of software in a hardware-agnostic manner.

---
## Practice

Virtualization allows us to abstract away the hardware. This enables us to use ??? physical machines for running and deploying our software.

* less
* more
* cheap
* fast

---
## Revision

A virtual machine allows us to emulate ???.

* hardware
* software
* cpu
* applications