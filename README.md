# VPN Manager - NordVPN control and server selection

**Package**: `@system/vpn`
**Version**: 0.1.0
**Repository**: `pkg-system-vpn`

## Overview

VPN Manager - NordVPN control and server selection

## Installation

### Prerequisites

This package requires the following external commands:

- `curl`
- `dmenu`
- `nordvpn`
- `systemctl`

### Using pkg-cli

```bash
# Install from GitHub
pkg-cli install @system/vpn

# Or install from local source
cd ~/.pkgs
stow vpn
```

## Usage

### System Integration

This package provides system integration for vpn manager - nordvpn control and server selection.


## Configuration

Configuration files are typically stored in:
- `~/.config/vpn/` - User configuration
- `~/.local/share/vpn/` - Application data

## Uninstallation

```bash
# Using pkg-cli
pkg-cli uninstall @system/vpn

# Or manual unstow
cd ~/.pkgs
stow -D vpn
```

## Development

See [CLAUDE.md](CLAUDE.md) for development guidelines and AI assistance instructions.

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Support

- **Issues**: [GitHub Issues](https://github.com/andronics/pkg-system-vpn/issues)
- **Discussions**: [GitHub Discussions](https://github.com/andronics/pkg-system-vpn/discussions)
- **Documentation**: [pkgs ecosystem docs](https://github.com/andronics/.pkgs)

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.
