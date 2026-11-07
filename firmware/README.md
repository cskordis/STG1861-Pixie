# Pixie video firmware

| JEDEC file | Intended system / use |
| --- | --- |
| `LINE.JED` | Line logic used with the 64 × 32 `FRAME.JED` configuration and the HEC1802 Mono machine configuration. |
| `FRAME.JED` | 64 × 32 video configuration for CHIP-8 and systems such as the COSMAC Elf and RCA Studio II. |
| `FRAME192.JED` | HEC1802 Mono machine configuration, intended to increase video resolution for ETI-660 Learner's Computer software. Use with `LINE.JED`. |

The files are device programming JEDEC images. Select the image that matches the target hardware and software configuration; verify device compatibility and programming requirements before programming.

> The filename is `FRAME192.JED` (not `FRAM192.JED`).
