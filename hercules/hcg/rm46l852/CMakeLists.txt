# Add include path
zephyr_include_directories(.)

# Add sources
zephyr_sources(src/errata_SSWF021_45.c)
zephyr_sources(src/esm.c)
zephyr_sources(src/gio.c)
zephyr_sources(src/notification.c)
zephyr_sources(src/pinmux.c)
zephyr_sources(src/rti.c)
zephyr_sources(src/sci.c)
zephyr_sources(src/sys_core.s)
zephyr_sources(src/sys_selftest.c)
zephyr_sources(src/sys_startup.c)
zephyr_sources(src/sys_vim.c)
zephyr_sources(src/system.c)
