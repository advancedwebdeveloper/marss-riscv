# Version 1.1a
- Added 16550A UART support (thanks to Marc Gauthier)
- Reworked the dram latency parameters to match the Sifive HiFive U540 Board
- Increased the dram dispatch queue size from 32 to 64
- Add a timestamp suffix to the stats file
- Bug fix: fixed the calculation of hardware page walk latency
- Bug fix: fixed the miscalculation in page fault counters
- Fixed Issue #2: memory leaks in copy_file
- Fixed Issue #3: 'log' instead 'log2'
