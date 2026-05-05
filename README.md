# Drone Remote Hardware

Hardware repository for the capstone drone remote and related board iterations.

This repo has been reorganized for clarity:

- `hardware/fcu/FCU-hardware/` -> FCU board design files
- `hardware/remote/FC_Remote-hardware/` -> remote controller board design files
- `hardware/remote/FC_Remote-hardware/nrf_breakout/` -> standalone nRF breakout board
- `mechanical/enclosure/` -> enclosure and mechanical CAD exports
- `docs/` -> organization notes and future hardware logs

## Primary Design Tools

- KiCad (schematic/PCB)
- STEP/STL/3MF for mechanical integration

## Suggested Navigation

1. Start in `hardware/remote/FC_Remote-hardware` for remote board files.
2. Open `hardware/fcu/FCU-hardware` for FCU board files.
3. Check `nrf_breakout` for the small adapter/breakout design.

## Notes

- Production artifacts and backups are preserved for traceability.
- Some legacy folders are still retained as historical snapshots.
