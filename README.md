# aoi6502

`aoi6502` is an experimental JIT-compiled NMOS 6502 emulator written in Rust.

The project is at an early stage. Its public API, architecture, and accuracy
targets have not been finalized yet.

## Goals

- Translate 6502 programs into native code instead of interpreting every
  instruction.
- Keep the generated code independent of a particular machine's memory map and
  peripherals.
- Preserve the observable behavior required to run real 6502 software.
- Document the design and its performance tradeoffs as the project develops.

## Status

The project has only just been initialized. There is no usable emulator yet.

## License

The emulator source is available under either of the following licenses, at
your option:

- [MIT](LICENSE-MIT)
- [Apache License 2.0](LICENSE-APACHE)
