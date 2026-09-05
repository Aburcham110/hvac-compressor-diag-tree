# HVAC Compressor Diagnostic Tree (Educational)

Python **stdlib-only** symptom-driven compressor tree (high discharge temp, floodback, short cycle, locked rotor, high amps) with optional SH/SC context, ranked checks, parts list, and LOTO reminders.

> **Educational only — incomplete stubs. Follow LOTO and OEM procedures.**

## Quick start

```bash
cd hvac-compressor-diag-tree
python3 compressor_diag.py --symptom high-amps --sh 8 --sc 12
python3 compressor_diag.py -i
```
