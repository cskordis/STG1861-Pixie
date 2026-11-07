# Bill of Materials (BOM)

This BOM is based on the released STG-1861 Pixie design revision 1.0c and the corresponding assembly CSV. Values below are verified against the provided schematic/component inventory and are intended for the released design revision only.

## Design identification

| Field | Value |
| --- | --- |
| Project | STG-1861 Pixie |
| Schematic revision | 1.0c |
| PCB revision | 1.0c |
| BOM revision / date | 1.0c |

## Components

| Reference(s) | Qty | Value / part number | Description | Footprint / package | Notes / source |
| --- | ---: | --- | --- | --- | --- |
| C1, C2, C3, C4 | 4 | 100 nF | Capacitor, ceramic | Capacitor_THT:C_Rect_L4.0mm_W2.5mm_P2.50mm | 4x capacitors; verify voltage rating and dielectric against the schematic if required by the assembled design |
| D5, D6 | 2 | 1N914 | Diode, switching | Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal | Datasheet: Vishay 1N914; confirm orientation and use in circuit |
| U1, U2 | 2 | ATF22C10 | IC, programmable logic | Package_DIP:DIP-24_W7.62mm | Confirm exact part revision / source and pinout against the design netlist |
| U3 | 1 | 74HC165 | IC, 8-bit parallel-in/serial-out shift register | Package_DIP:DIP-16_W7.62mm | Nexperia 74HC165 datasheet: https://assets.nexperia.com/documents/data-sheet/74HC_HCT165.pdf |
| U4 | 1 | 4040 | IC, 12-stage binary ripple counter | Package_DIP:DIP-16_W7.62mm | Intersil CD4040B family datasheet; confirm pinout and device variant |
| U5 | 1 | CDP1861 | IC, custom/legacy logic device | Package_DIP:DIP-24_W15.24mm_Socket | Legacy device; confirm exact package/socket compatibility and sourcing |

## Assembly notes

- Use the reference designators and quantities exactly as listed above for the released 1.0c revision.
- Verify polarity, orientation, and device variant for all semiconductor parts before assembly.
- Confirm socketing and package compatibility for U5 (CDP1861) against the PCB and assembly documentation.
- Record any substitutions, lot-specific variations, or approved alternatives in the design change log.
- Do not substitute parts without confirming electrical ratings, pinout, and footprint compatibility.

## Change history

| BOM revision | Date | Change | Author |
| --- | --- | --- | --- |
| 1.0c | TBD | Initial BOM entry based on STG1861c.csv component inventory | TBD |
