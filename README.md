# Seaver Olson

Computer science at Loyola Chicago. I’m interested in the uncomfortable parts of
systems work: privilege boundaries, machine state, and what actually happens
between an instruction and the hardware it is meant to describe.

Right now I’m adding Intel VMX support to gem5. The work has reached the useful
stage: a small 64-bit guest can enter VMX operation, launch, take a few selected
VM exits, resume, and hand control back to the host.

```text
host ── VM entry ──> guest
  ^                    │
  └────── VM exit ─────┘
```

## On the bench

| Project | What I’m doing there |
| --- | --- |
| [gem5-vmx](https://github.com/seaver-olson/gem5-vmx) | Intel VMX for gem5’s x86 full-system simulator. |
| [VeriVerto](https://github.com/seaver-olson/VeriVerto) | A five-stage RV32I processor in Verilog: hazards, forwarding, branches, and some experimental cache work. |
| [archspec](https://github.com/seaver-olson/archspec) | An early C++ library for gathering structured information about a Linux machine. |
| [PEENOS](https://github.com/seaver-olson/PEENOS) | A small bare-metal ARMv8 operating system for a Raspberry Pi 3B. |

## Elsewhere

I read architecture manuals for fun, keep too many browser tabs open while
debugging, and grow plants. The plants are generally more forgiving than the
simulator.
