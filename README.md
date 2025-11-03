# Fabric Agent Downloads

Official distribution repository for Fabric Agent builds.

## Available Downloads

### macOS

#### Apple Silicon (M1, M2, M3, M4)
- **Version**: 1.0.0
- **File**: `FabricAgent-Silicon-v1.0.0.zip`
- **SHA256**: See `SHA256-Silicon.txt`
- **Size**: ~600MB
- **Min macOS**: 12.0 (Monterey)

#### Intel (x86_64)
- **Version**: 1.0.0
- **File**: `FabricAgent-Intel-v1.0.0.zip`
- **SHA256**: See `SHA256-Intel.txt`
- **Size**: ~600MB
- **Min macOS**: 12.0 (Monterey)

### Windows (Coming Soon)
- Windows 10/11 (x64)

### Linux (Coming Soon)
- Ubuntu 20.04+ / Debian 11+
- Fedora 35+ / RHEL 8+

## Installation

### macOS
1. Download the appropriate ZIP for your Mac (Silicon or Intel)
2. Extract the ZIP file
3. Move `FabricAgent.app` to `/Applications`
4. Right-click and select "Open" on first launch
5. Follow on-screen enrollment instructions

## Verification

Always verify the download with SHA256 checksum:

```bash
# Silicon
shasum -a 256 -c SHA256-Silicon.txt

# Intel
shasum -a 256 -c SHA256-Intel.txt
```

## Auto-Update

The agent includes auto-update functionality. It checks for updates on startup and downloads them in the background.

## Support

- **Documentation**: [GitHub Wiki](https://github.com/Carmel-Labs-Inc)
- **Issues**: [GitHub Issues](https://github.com/Carmel-Labs-Inc/fabric-intel/issues)
- **Email**: support@carmel.ai

## License

Proprietary - See EULA in the application package.
