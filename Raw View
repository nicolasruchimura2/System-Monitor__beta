# System-Monitor__beta




# Core Components
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Data Layer    │────│  Display Layer  │────│   Input Layer   │
│  (collectors)   │    │   (ncurses)     │    │  (keyboard)     │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         └───────────────────────┼───────────────────────┘
                                 │
                    ┌─────────────────┐
                    │  Control Loop   │
                    │   (main.c)      │
                    └─────────────────┘

# File Structure:

sysmon/
├── src/
│   ├── main.c          # Main loop & coordination
│   ├── collectors/
│   │   ├── cpu.c       # CPU usage collection
│   │   ├── memory.c    # Memory stats
│   │   ├── network.c   # Network I/O
│   │   ├── disk.c      # Disk usage/I/O
│   │   └── process.c   # Process information
│   ├── display/
│   │   ├── dashboard.c # Main dashboard layout
│   │   ├── widgets.c   # Individual widgets (bars, graphs)
│   │   └── themes.c    # Color schemes
│   └── utils/
│       ├── ringbuffer.c # For storing historical data
│       └── config.c     # Configuration handling
├── include/
└── Makefile
