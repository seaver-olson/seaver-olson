# Seaver Olson

Computer science at Loyola Chicago. I’m interested in computer architecture, HPC and virtualization.

Right now I’m adding Intel VMX support to gem5. The work has reached the useful
stage: a small 64-bit guest can enter VMX operation, launch, take a few selected
VM exits, resume, and hand control back to the host.

```text
host ── VM entry ──> guest
  ^                    │
  └────── VM exit ─────┘
```

## Projects

*   [gem5-vmx](https://github.com/seaver-olson/gem5-vmx) | Intel VMX for gem5’s x86 full-system simulator.
*   [VeriVerto](https://github.com/seaver-olson/VeriVerto) | A five-stage RV32I processor in Verilog: hazards, forwarding, branches, and some experimental cache work.
*   [archspec](https://github.com/seaver-olson/archspec) | An early C++ library for gathering structured information about a Linux machine.
*   [PEENOS](https://github.com/seaver-olson/PEENOS) | A small bare-metal ARMv8 operating system for a Raspberry Pi 3B.

## Plants

I will add pictures of my favorite plants here soon when they bloom!
