# Build Notes

This document captures the practical notes for assembling the STG-AVI1861 compact Pixie variant.

## Assembly goals

- Use through-hole components only
- Keep the footprint smaller than the original STG1861 Pixie board
- Prioritize hand assembly and serviceability
- Preserve the original circuit intent while adapting the layout

## Recommended workflow

1. Verify the schematic against the original STG1861 design and the compact footprint changes.
2. Print the PCB layout at full size and confirm component spacing before drilling or ordering boards.
3. Start with the lowest-profile / smallest-pitch components first.
4. Install all resistors, capacitors, and diodes before soldering larger parts.
5. Test each stage before final enclosure installation.
6. Check for mechanical clearance in the chosen enclosure or panel layout.

## Layout considerations

- Maintain generous spacing around high-impedance analog nodes.
- Keep grounding paths short and consistent.
- Separate audio signal routing from power supply routing where practical.
- Leave clearance for hand-soldering and future modification.

## Testing checklist

- Continuity and short checks before power-up
- Confirm correct power polarity and supply rails
- Measure DC bias points at key circuit nodes
- Check for unwanted oscillation or instability
- Listen for audible noise, hum, or clipping issues
- Verify the enclosure fit with the assembled board

## Notes

This document is intentionally lightweight and is intended to be updated as the board design evolves.
