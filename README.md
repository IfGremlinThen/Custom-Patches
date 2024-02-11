## Loop Hero
Updates to Linux break compatability with Loop Hero due to it's use of deprecated 32-bit libraries.

**Problem:** Loop Hero fails to launch.

**Error:** `libssl.so.1.1: cannot open shared object file: No such file or directory`

**Solution:** Drag-and-drop included the libraries into `/usr/lib/x86_64-linux-gnu`.  Requires root access.
