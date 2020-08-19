# Sub-Store
> This project is still under active development. Current version: v0.1 (backend only).

Subscription manager for QX, Loon and Surge.
Core functionality:
1. Conversion among various formats.
2. Subscription formatting.
3. Collect multiple subscription in one URL.
## 1. Subscription Conversion
### Supported input formats
- [x] SS URI
- [x] SSR URI
- [x] V2RayN URI
- [x] QX (SS, SSR, VMess, Trojan, HTTP)
- [x] Loon (SS, SSR, VMess, Trojan, HTTP)
- [x] Surge (SS, VMess, Trojan, HTTP)

### Supported target platforms
- [x] QX
- [x] Loon
- [x] Surge

## 2. Subscription Formatting
### Filtering
- [x] **Keyword filter**
- [x] **Discard keywords filter**
- [x] **Regex filter**
- [x] **Discard regex filter**
- [x] **Region filter**
- [x] **Type filter**
- [x] **Useless proxies filter**
- [x] **Script filter**

### Proxy Operations
- [x] **Set property operator**: set some proxy properties such as `udp`,`tfo`, `skip-cert-verify` etc.
- [x] **Flag operator**: add flags or remove flags for proxies.
- [x] **Sort operator**: sort proxies by name.
- [x] **Keyword sort operator**: sort proxies by keywords (fallback to normal sort).
- [x] **Keyword rename operator**: replace by keywords in proxy names.
- [x] **Keyword delete operator**: delete by keywords in proxy names.
- [x] **Regex rename operator**: replace by regex in proxy names.
- [x] **Regex delete operator**: delete by regex in proxy names.
- [x] **Script operator**: modify proxy by script.

