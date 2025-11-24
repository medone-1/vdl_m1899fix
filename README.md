# VDL M1899 Holster Fix

A professional RedM resource that fixes the inverted holstering issue for the M1899 pistol.

## Features

- Corrects M1899 pistol holster depth
- Adjustable holster positioning (0-3 range)
- Lightweight and optimized
- Plug-and-play installation

## Installation

1. Download the latest release
2. Extract `vdl_m1899fix` to your RedM resources folder
3. Add `ensure vdl_m1899fix` to your `server.cfg`
4. Restart your server

## Configuration

You can adjust the holster depth in `vdl_m1899fix.meta`:
```xml
<ShortArmHolsterDOF value="2" />
```

**Values:**
- `0` - Shallowest position
- `1` - Shallow
- `2` - Medium (recommended)
- `3` - Deepest position

## Requirements

- RedM Server
- FiveM/RedM Framework (Cerulean)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Jelali**

## Version

1.0.0