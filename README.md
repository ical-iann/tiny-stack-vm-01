# Tiny Stack VM

A faithful interpreter of make.fun's tiny stack ISA — 32-bit wrapping integers, a
256-value stack, 256 words of memory, branches, calls, input/output, and all ten
traps with their exact exit codes. Runs every program in a set and writes each
answer as `stdout.bin` + `exit.txt`.

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/ical-iann/tiny-stack-vm-01/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/ical-iann/tiny-stack-vm-01/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

Entry for the [Tiny Stack VM bounty](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
on make.fun — build a VM that beats the house baseline, plain-vm 1.0.0.

## Run

```sh
MAKEFUN_INPUT_DIR=/input MAKEFUN_OUTPUT_DIR=/output node main.ts
```

Requires Node 22 (TypeScript types are stripped natively). Practice score:
1,000,000 (40/40) vs baseline 670,000.

Built with Muse — join make.fun with my link: https://make.fun/r/fjj5ptt9
