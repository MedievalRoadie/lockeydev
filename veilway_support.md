# Veilway Support

Welcome to Veilway, a WireGuard VPN client for Apple devices.

## Getting Started

Veilway is a **client application** for the WireGuard VPN protocol. To use Veilway, you'll need a WireGuard configuration from your VPN provider or self-hosted server.

### Adding a Tunnel

There are three ways to add a VPN tunnel:

#### 1. QR Code (Recommended)
1. Tap the **+** button
2. Select **Scan QR Code**
3. Point your camera at the WireGuard QR code from your provider
4. Give your tunnel a name and tap **Save**

#### 2. Import File
1. Tap the **+** button
2. Select **Import from File**
3. Choose a `.conf` file from your device
4. Give your tunnel a name and tap **Save**

#### 3. Manual Entry
1. Tap the **+** button
2. Select **Add Manually**
3. Enter your WireGuard configuration details
4. Tap **Save**

### Connecting

- Tap on a tunnel to view its details
- Tap the **Connect** button to establish the VPN connection
- The status indicator shows your connection state:
  - 🟢 **Green** - Connected
  - 🟡 **Yellow** - Connecting
  - 🔴 **Red** - Disconnected

### Disconnecting

- Tap the **Disconnect** button on the active tunnel
- Or tap on a different tunnel to switch connections

## Managing Tunnels

### Edit a Tunnel
1. Tap on the tunnel to open details
2. Tap **Edit** in the top right
3. Make your changes and tap **Save**

### Delete a Tunnel
- Swipe left on a tunnel in the list and tap **Delete**
- Or tap **Edit** on the tunnel details and select **Delete Tunnel**

### On-Demand Connection (iOS/macOS)
Configure automatic VPN connection based on network conditions:
1. Open tunnel details
2. Tap **On-Demand**
3. Choose when to automatically connect:
   - On Wi-Fi networks
   - On cellular
   - On specific networks

## Platform-Specific Notes

### iOS & iPadOS
- VPN status appears in the status bar when connected
- Connection persists in the background
- Use Control Center for quick access

### macOS
- Menu bar icon shows connection status
- Right-click for quick connect/disconnect

### Apple TV
- Use the Siri Remote to navigate
- Import configurations via iCloud sync from your iPhone/iPad/Mac

## iCloud Sync

Veilway can sync your tunnel configurations across devices:

1. Ensure iCloud is enabled on your devices
2. Configurations sync automatically

## Troubleshooting

### Cannot Connect
- Verify your configuration is correct
- Check your internet connection
- Ensure the VPN server is online
- Try removing and re-adding the tunnel

### Connection Drops Frequently
- Check your network stability
- Try a different server endpoint if available
- Verify the server hasn't changed its configuration

### QR Code Won't Scan
- Ensure adequate lighting
- Hold the camera steady
- Make sure the entire QR code is visible
- Try importing via file instead

### Configuration Not Syncing
- Check that iCloud is enabled
- Ensure you're signed into the same Apple ID
- Check iCloud storage isn't full

## Getting a WireGuard Configuration

Veilway requires a WireGuard configuration. You can obtain one from:

- **Commercial VPN providers** that support WireGuard (Mullvad, IVPN, ProtonVPN, etc.)
- **Self-hosted servers** using WireGuard on your own infrastructure

Contact your VPN provider for setup instructions specific to their service.

## Privacy & Security

- Veilway collects **no data** whatsoever
- Private keys are stored in your device's secure Keychain
- All VPN traffic is encrypted using WireGuard's modern cryptography
- We have no visibility into your connections or traffic

## Contact Support

If you experience any weirdnesses or bugs, or have any suggestions for improvements:

- **Email**: veilway@lockeydev.com

---

*Veilway is not a VPN service. We provide the client software - you bring your own WireGuard configuration.*
