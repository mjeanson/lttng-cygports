# LTTng cygports

1. Install cygport via Cygwin's installer.

2. Download source and perform all build steps.

  ```
    $ cygport liburcu/liburcu.cygport download all
    $ cygport babeltrace/babeltrace.cygport download all
  ```

  If cygport warns about missing dependencies, install them via Cygwin's installer and run all build steps again.

3. Currently, none of our cygports needs a postinstall script; it is enough to unpack to ``/``.

  ```
    $ tar xvfJ liburcu/liburcu-0.9.3-1.x86/dist/liburcu/liburcu-0.9.3-1.tar.xz -C /
    $ tar xvfJ babeltrace/babeltrace-1.5.1-1.x86/dist/babeltrace/babeltrace-1.5.1-1.tar.xz -C /
  ```
