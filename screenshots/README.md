# Runtime screenshots

These rendered terminal screenshots show output captured from the current repository build in Ubuntu on WSL on 2026-11-02. The CLI and container lifecycle captures use the real supervisor and static fixture under a temporary root filesystem. The workload capture shows output from the real `cpu_hog` and `io_pulse` binaries.

- [`runtime-cli.png`](runtime-cli.png): CLI help, a completed `run`, process listing, and container logs.
- [`container-lifecycle.png`](container-lifecycle.png): start, logs, stop, and the resulting process state.
- [`workloads.png`](workloads.png): CPU and I/O workload output.

The optional kernel memory monitor is not pictured; exercising it requires a separately built module and a VM that permits loading it.
