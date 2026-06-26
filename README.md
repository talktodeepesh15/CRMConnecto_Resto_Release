# Connect2 Resto — Getting Started Guide

## 1. Download

Download the latest version for your operating system from the [Releases page](https://github.com/anomalyco/CRMConnecto-Resto/releases).

| OS | File |
|---|------|
| **macOS (Intel)** | `Connect2-Resto-x86_64-apple-darwin.zip` |
| **macOS (Apple Silicon)** | `Connect2-Resto-aarch64-apple-darwin.zip` |
| **Windows** | `Connect2-Resto-x86_64-pc-windows-msvc.zip` |
| **Linux** | `Connect2-Resto-x86_64-unknown-linux-gnu.tar.gz` |

## 2. Run

Extract the zip archive and run the application:

- **macOS:** Double-click `Connect2-Resto.app`
- **Windows:** Double-click `resto-app.exe`
- **Linux:** Run `./resto-app` in the terminal

The server starts on `http://localhost:8080`. A browser tab will open automatically.

## 3. Activate 1-Hour Demo

1. Open `http://localhost:8080/license` in your browser
2. Type **`demo`** in the license key field
3. Click **Activate License**
4. Click **Continue to Login**

## 4. Log In & Explore

| Role | URL | Credentials |
|------|-----|-------------|
| **Manager** | `http://localhost:8080/manager/login` | Username: `admin`, Password: `admin` |
| **Kitchen** | `http://localhost:8080/kitchen/login` | PIN: `1234567890` |
| **Server** | `http://localhost:8080/server/login` | PIN: `0987654321` |
| **Customer** | `http://localhost:8080/customer` | No login required |

## 5. What Happens When Demo Ends

After 1 hour, all demo data is automatically wiped and the system resets to defaults. You can start a new demo session anytime by entering `demo` again.
