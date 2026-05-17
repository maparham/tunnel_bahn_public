# TunnelBahn — Help & support

**TunnelBahn** is a native **macOS** app for connecting through **WireGuard** with optional **per-app routing**: you choose which applications use the VPN; other traffic can stay on your normal network path, depending on your settings.

This page is intended for users who downloaded TunnelBahn from the **Mac App Store** (when available) or from other distribution you received from the publisher.

---

## First launch & permissions

- macOS may ask you to **allow TunnelBahn to add VPN configurations**. This is expected for any VPN-style app using system networking APIs.
- You need a valid **WireGuard configuration** from your administrator, VPN provider, or workplace. TunnelBahn does not sell or host VPN subscriptions.

---

## Getting connected

1. **Import your profile** (for example via a `.conf` file from your trusted source).
2. **Activate the tunnel** from the TunnelBahn window or menu extra.
3. If you use **per-app routing**, review in-app routing settings so only the intended apps use the tunnel; misconfiguration can leak traffic outside the tunnel.

---

## Common issues

| Issue | Things to try |
|--------|----------------|
| Tunnel won’t start | Quit and reopen TunnelBahn; check System Settings → Network for duplicate or stale VPN entries; reinstall only from a trusted source. |
| Some apps bypass the VPN | With per-app routing, only selected apps may be routed; firewall or other VPN/proxy extensions can interfere—disable conflicting tools as a diagnostic step. |
| No internet when connected | Your profile’s Allowed IPs and DNS settings may route too much traffic; validate the profile with your provider. |

Still stuck? **[Open an issue](https://github.com/maparham/tunnel_bahn_public/issues)** on this repository (enable Issues in repo settings if the link fails) or use the publisher’s email if they provided one on the Mac App Store product page.

---

## Privacy policy

TunnelBahn’s privacy policy lives here:

**[Privacy policy (`PRIVACY.md`)](./PRIVACY.md)**

Rendered on GitHub: `https://github.com/maparham/tunnel_bahn_public/blob/main/PRIVACY.md`

---

## Note about this repository

This public repository publishes **privacy and support documents** only. Full application source distribution may live elsewhere subject to the publisher’s release policy.
