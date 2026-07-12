<p align="center">
  <img src="./assets/forest-header.svg" width="100%" alt="Seaver Olson - Loyola Chicago systems researcher">
</p>

<p align="center">
  <strong>Computer science student at Loyola University Chicago</strong><br>
  Computer architecture · Virtualization · Operating systems · Simulation
</p>

<p align="center">
  <a href="https://github.com/seaver-olson/gem5-vmx">gem5-vmx</a> ·
  <a href="https://github.com/seaver-olson/VeriVerto">VeriVerto</a> ·
  <a href="https://github.com/seaver-olson/archspec">archspec</a> ·
  <a href="https://github.com/seaver-olson/PEENOS">PEENOS</a>
</p>

---

## Current expedition

I am extending **gem5's x86 full-system simulator with Intel VMX support**, building the architectural machinery needed to model hypervisor-aware systems. My work lives where instruction semantics, privilege boundaries, simulated hardware, and operating systems meet.

~~~text
guest software
    ↓
VMX transitions + privileged state
    ↓
gem5 x86 full-system simulation
    ↓
architectural behavior we can inspect
~~~

## Systems I am growing

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/seaver-olson/gem5-vmx">gem5-vmx</a></h3>
      Intel VMX support for gem5, enabling virtualization-aware x86 full-system simulation.
      <br><br><code>C++</code> <code>x86</code> <code>VMX</code> <code>simulation</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/seaver-olson/VeriVerto">VeriVerto</a></h3>
      An RV32I processor built in Verilog for exploring pipelines and architectural behavior.
      <br><br><code>Verilog</code> <code>RISC-V</code> <code>CPU design</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/seaver-olson/archspec">archspec</a></h3>
      A C++ library for hardware and software introspection across the system boundary.
      <br><br><code>C++</code> <code>introspection</code> <code>systems</code>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/seaver-olson/PEENOS">PEENOS</a></h3>
      An AArch64 Raspberry Pi operating-system exploration, close to the metal.
      <br><br><code>AArch64</code> <code>Raspberry Pi</code> <code>bare metal</code>
    </td>
  </tr>
</table>

## Forest floor

I am interested in the parts of a computer that ordinary software gets to forget: page tables, privilege levels, trap paths, device state, instruction semantics, and the contracts between hardware and software.

Outside the machine, I also like **plants**: complicated systems with excellent power management.

~~~text
hardware → architecture → virtualization → kernel → userspace
                 ↑ the interesting layers are down here
~~~

<p align="center"><sub>Built from plain Markdown, GitHub-safe HTML, and one repository-owned SVG.</sub></p>
