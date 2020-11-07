File bios_cfg.text contains definitions needed by both PROM project, the bootstrap loader, the monitor, and perhaps other low-level code.  Ideally, there'd be one copy of this file shared by all the projects that needed it, but at the moment it is duplicated in each project.  These duplicates must be kept in sync manually.

Directories prom0 and prom1 contain the source for the two BIOS PROMs.
