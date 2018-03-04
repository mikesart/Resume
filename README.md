## Michael Sartain  
mikesart@fastmail.com  

## Overview

Experienced C / C++ / x86 assembly graphics and systems programmer. 25+ years building and shipping products, most working on graphics and performance on projects spanning Windows, Linux, Mac OS, and Sony / Microsoft / Nintendo game consoles.

## Experience

### Valve Software and RAD Game Tools contractor (2016 - PRESENT)

* Gpuvis primary developer (Linux GPU Trace Visualizer)
* Linux trace-cmd (ftrace front-end) thread group id feature work, several bug fixes
* Linux kernel ftrace tgid feature patches
* SDL2 Linux realtimekit thread priority patches
* Wrote RAD L2TP RADIUS two-factor vpn plugin (https://github.com/mikesart/radauth)

### Valve Software (2011 - 2016)

* Ported Source 2 game engine code to 64-bit
  * 13+ year old 32-bit codebase shipped with over 15 games from 2004-2011
* Developer on Dota 2
  * Performance optimization work, bug fixing
  * Convert network layer and game to use Google Protocol Buffers and Snappy
  * Wrote fog of war system working closely with primary game designer
  * Wrote FoW 2D viewer system, which also helped visualize entity bugs
  * Wrote replay system: scrubbing, debugging, jumping, broadcast, dvr features
     * Code: https://developer.valvesoftware.com/wiki/Dota_2_Demo_Format
  * Linux Dota 2 server optimizations, remote server debugging (Europe clusters, etc)
* Founded Valve Linux team with co-workers Scott Ludwig and Rick Johnson
  * Interviewed, hired, and built team to 13 developers
  * Ported Steam, L4D2, TF2, Half Life, Portal, Portal 2, CS:GO, Day of Defeat to Linux
  * TF2 was first AAA title on Linux: Initial port ran at 6fps, with several 300ms stalls
  * Worked with NVIDIA, Intel, and AMD on Linux OpenGL graphics driver bugs and perf issues
  * Over 3,000 native games available on Steam Linux as of February, 2017
* Developer on Portal 2, Team Fortress 2, CS:GO working on performance issues, debugging,  optimization, and Linux server cluster stability
* Virtual Reality graphics performance development work plus investigate and fix threading bugs
* Contribute feature and bug fix patches to Linux LLDB Debugger
* Contributed over 200 feature and bug fixes to cgdb (ncurses gdb frontend)

### RAD Game Tools (2001 - 2011)

* Ported Bink Video Codec to GameCube, Xbox, and PS2 consoles
* Contracted with Bungie for Halo 2 optimization work
* Primary developer with Michael Abrash on Pixomatic Software Renderer. Used in:
  * Unreal Tournament 2003/2004, Dungeon Siege, MS Flight Simulator, Lionheart, Medal of Honor, Sims 2, EA, Logitech, among many others. Sold to Intel in 2006.
* RAD Developer on Intel Larrabee project
  * Worked closely with Dean Macri and Will Damon currently at Apple
* Wrote d3d capture/playback graphics performance, debugger, and validation tool

### Microsoft Xbox ATG Group (1999 - 2001)

* Developer researching Xbox & NVIDIA NV2A performance characteristics with Michael Abrash
* Wrote and optimized Xbox graphics samples and architecture white papers
* Optimized Xbox graphics driver, investigated & fixed bugs
* Wrote NV2A perf register sampling code which was used to create Xbox PIX tool
* Worked with and contributed source to several companies optimizing launch title games:
  * Halo, Half-Life, Orange Box, Oddworld: Munch’s Oddysee

### Microsoft Games (1996 - 1999)

* Lead tech, graphics, and AI developer on NFL Fever 2000
  * First game started and developed internally at Microsoft
* Integrated, tested, and fixed bugs with NFL Fever 2000 software renderer
* Assisted Andy Glaister with GameOS features (Internal graphics debugging / profiling tool)
* Optimization development work on Baseball, Crimson Skies, MechWarrior

### Microsoft Mail Business Unit Senior Developer (1991 - 1996)

* Microsoft Mail & Schedule+ (1992)
* Windows 95 email client (1995)
* Exchange Server v1.0 & v4.0 (1996)
* Windows NT email client (1996)
* Exchange Server v5.0 (1997)
* Dev lead on Microsoft Highlander client team (~11 developers)
* Wrote FileVer and NetWatch utilities which were added to Windows NT Resource Kit

## Open Source Development Work

### gpuvis - GPU Trace Visualizer, similar to GPUView on Windows

* https://github.com/mikesart/gpuvis
* https://github.com/mikesart/gpuvis/wiki/Overview

### trace-cmd commits - utility for Linux ftrace

* https://git.kernel.org/pub/scm/linux/kernel/git/rostedt/trace-cmd.git/log/?qt=grep&q=sartain

### Linux kernel commits

* 6d36ce2 tools lib traceevent: Add UL suffix to MISSING_EVENTS
* 952a99c tools lib traceevent: Fix bad force_token escape sequence
* 99c621d tracing: Add saved_tgids file to show cached pid to tgid mappings
* 4da14d5 staging: greybus: firmware: Convert sscanf calls to strtoul
* afb5fdf staging: greybus: firmware: Change long long unsigned to unsigned long long
* 5099c4c staging: greybus: firmware: Remove extra braces from single line if
* 0c38018 staging: greybus: firmware: Remove trailing semicolon from FW_TIMEOUT_DEFAULT

### cgdb work - ncurses gdb frontend (over 200 feature & bug fix commits)

* https://github.com/mikesart/cgdb-mikesart

### Valve Software Linux OpenGL Benchmarking tool
* https://github.com/ValveSoftware/voglperf

### Minor usbview buffer over-read fix

* https://github.com/gregkh/usbview/commit/bef1aac68881b774c427200b360ca61fce134e10

### Simple DirectMedia Layer (SDL2) patches
* https://hg.libsdl.org/SDL/log
* 2018-04-23 | Added support for adjusting thread priorities using Linux RealtimeKit.
* 2013-02-14 | Clear relative mouse mode and restore when bringing up sdl message box.
* 2013-02-05 | Add defines to disable setlocale and fork. Disable that code by default for now.
* 2013-02-05 | Use left facing arrow instead of right facing arrow for system cursor.
* 2012-11-19 | Add SDL_CreateSystemCursor for Windows and Linux.
* 2012-10-11 | Add GLX_X_VISUAL_TYPE_EXT so created window will use DirectColor if available (instead of TrueColor).
* 2012-10-11 | Add XInitThreads to X11_CreateDevice.
* 2012-10-11 | Fix Colormap when using X11_SetWindowFullscreenViaWM() path.

### Pixomatic features (DX9 compatible software renderer)

* http://www.radgametools.com/cn/pixofeat.htm

### Dr. Dobbs optimizing Pixomatic articles (by Michael Abrash)

* http://www.drdobbs.com/architecture-and-design/optimizing-pixomatic-for-x86-processors/184405765
* http://www.drdobbs.com/optimizing-pixomatic-for-modern-x86-proc/184405807
* http://www.drdobbs.com/optimizing-pixomatic-for-modern-x86-proc/184405848

### Random articles about projects I’ve contributed to

* http://www.phoronix.com/scan.php?page=article&item=valve_linux_sdl&num=1
* http://www.develop-online.net/news/valve-hires-world-class-development-trio/0109284
* http://www.pcgamer.com/valve-joins-linux-foundation/
* https://venturebeat.com/2011/11/14/making-of-the-xbox-1/view-all/
* http://blogs.valvesoftware.com/linux/steamd-penguins/
* http://blogs.valvesoftware.com/linux/faster-zombies/
* http://www.drdobbs.com/parallel/a-first-look-at-the-larrabee-new-instruc/216402188
* http://www.drdobbs.com/parallel/rasterization-on-larrabee/217200602

### LLDB Debugger Commits

* https://hg.libsdl.org/SDL/log
* Merge RegisterContextPOSIX_x86_64 and RegisterContextPOSIX_i386 into RegisterContextPOSIX_x86
* Re-enable test_convenience_registers_16bit_with_process_attach test for Linux.
* Clean up RegisterContextPOSIX i386 code. Use 32-bit register enums without gaps on 64-bit hosts. Don't show 64-bit registers when debugging 32-bit
* Remove unused local variable.
* fix class/struct mismatch warning
* Clean up RegisterContextPOSIX. Renamed to POSIXBreakpointProtocol. Will clean up header files and m_register_infos shortly.
* Cleanup POSIX RegisterContext class hierarchies.
* warning cleanup (use LLDB_INVALID_HOST_THREAD instead of NULL)
* unused variable, typedef requires name warning cleanup
* Round plt entsize to addralign
* add register name to UnwindLog error message
* A clang::Type::Decayed type to kill compile warning
* add error checking and messages to 'target modules show-unwind' command
* clean up about 22 warnings messages
* Initialize m_leak member variable.
* Fix Linux Host::GetCurrentThreadID() to return real tid (not pthread_t). This fixes threadname logging (--thread-name) Add "-t" to TestLogging.py
* Fix thread name updating in Linux. "thread list" should report correct names always now. Created new LinuxThread class inherited from POSIXThread
* Optimize Host::GetThreadName() to read from /proc/$TID per Matt's suggestion.
* Add format specifiers to various format ids so we can print thread ids in decimal on Linux and FreeBSD.
* simple plugin now works with Linux fix assert in SetPluginInfo implement Linux ePathTypeLLDBSystemPlugins and ePathTypeLLDBUserPlugins implement 
* Fix Rendezvous breakpoint to only be set once, resolve addr in BreakpointLocationList::FindByAddress
* Fix "source list -n printf" on Linux (printf is symbol alias for __printf)
* Add silent option to command source. Patch from Matthew Sorrels
* Use target DisplaySource if available so we can get mixed source and assembly.
* Symbol prologue code checks if funciton lines up with symbol and uses function prologue code with line info if so.
* Fix ObjectFileELF crc32 code used when no build id is present.
* Add split symbol support to test makefile & add linux split symbol test case.
* Split symbol support for ELF and Linux.
* Add new files to CMakeLists.txt to fix cmake build error.
* Add newer Linux AT_ defines from elf.h.
* Remove extra modules.Append() as it causes dupes in the m_images array. (Used with image list, etc.)
* Fix unitialized variable in AuxVector::GetEntryName() which crashed in AuxVector::DumpToLog
* ObjectFileELF::GetModuleSpecifications on Linux should work now. Which means "platform process list" should work and list the architecture.
* Add ${ansi.XX} parsing to lldb prompt, use-color setting, and -no-use-colors command line options.
* Comment out ObjectFileELF::GetModuleSpecifications() function until I can debug where it's causing tests to fail.
* Implement ObjectFileELF::GetModuleSpecifications(), and add PlatformLinux code to deal with unknown arch properties.
