# UFW Firewall Configuration

Secured the server by configuring **UFW (Uncomplicated Firewall)** to enforce a minimal attack surface, allowing only essential services.

### ⚙️ Applied Rules:

- ✅ **Enabled** UFW to activate the firewall
- ✅ **Allowed incoming connections** on:
  - `22` (SSH) — for remote server access
  - `80` (HTTP) and `443` (HTTPS) — for web server functionality
- ❌ **Explicitly denied**:
  - `3306` (MySQL) — to prevent external database access

### 🔍 Verification:

- Confirmed active firewall rules using:
  ```bash
  sudo ufw status
