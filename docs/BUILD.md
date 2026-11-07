# Build and Verification Checklist

This checklist is a general workflow for the STG-AVI1861. Follow the released schematic, PCB revision, and component documentation for all electrical details; this document does not specify circuit values, supply requirements, or expected test voltages.

## Before assembly

- [ ] Confirm the schematic, PCB, and BOM revisions match.
- [ ] Review the released design files and applicable build notes.
- [ ] Check that all parts match the BOM, including package, pinout, polarity, and ratings.
- [ ] Inspect the bare PCB for damage, shorts, missing pads, or manufacturing defects.
- [ ] Confirm the board fits the intended enclosure and that connector/control clearances are adequate.
- [ ] Gather appropriate soldering, ESD, and eye-protection equipment.

## Assembly

- [ ] Install components according to the assembly drawing or PCB silkscreen.
- [ ] Observe polarity and pin-1 markings for polarized or orientation-sensitive parts.
- [ ] Check component orientation and placement before soldering each group.
- [ ] Inspect solder joints for bridges, poor wetting, and unsoldered connections.
- [ ] Clean the board only using a method suitable for the components and PCB materials.

## Unpowered inspection

- [ ] Compare the populated board against the assembly drawing and BOM.
- [ ] Check for solder bridges, misplaced parts, clipped leads, and debris.
- [ ] Use the schematic to check for unintended shorts between power and ground; account for normal circuit paths when interpreting continuity readings.
- [ ] Verify connector wiring and polarity against the released design documentation.

## Power-up and functional verification

- [ ] Use only the supply type, polarity, and operating conditions specified by the released design.
- [ ] If the design documentation provides a staged or current-limited bring-up procedure, follow it.
- [ ] Measure only the documented test points and compare results with the documented expected values.
- [ ] Verify inputs, outputs, controls, and other functions using the design's test procedure.
- [ ] Record any deviations, symptoms, measurements, and the hardware revision tested.

## Before enclosure installation

- [ ] Confirm mechanical fit without stressing the PCB or component leads.
- [ ] Ensure no exposed conductors can contact the enclosure or other hardware unintentionally.
- [ ] Recheck wiring and operation after installation.

## Build record

| Field | Value |
| --- | --- |
| Assembled by / date | TBD |
| PCB revision | TBD |
| BOM revision | TBD |
| Test procedure / revision | TBD |
| Results and notes | TBD |
