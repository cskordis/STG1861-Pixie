# Pixie video firmware

| JEDEC file | Intended system / use |
| --- | --- |
| `LINE.JED` | Line-logic image for the 64 × 32 `FRAME.JED` configuration on HEC-1802 Color or Mono systems. |
| `FRAME.JED` | 64 × 32 video configuration for CHIP-8 and systems such as the COSMAC Elf and RCA Studio II. Use with the HEC-1802 ROM. |
| `FRAME192.JED` | HEC-1802 Color or Mono configuration providing 64 × 48 video for ETI-660 Learner's Computer software. Use with `LINE.JED` and the ETI-660 ROM. |

These files are JEDEC images for programming the video logic devices. Choose the image or combination of images that matches your hardware and software configuration, and verify device compatibility and programming requirements before programming.
