# PowerShell Utility Scripts

A curated collection of PowerShell scripts for system administration, network monitoring, security scanning, and automation tasks.

## 📋 Overview

This repository contains practical PowerShell utilities designed to simplify common administrative workflows, enhance security posture, and provide quick insights into system behavior.

## 🚀 Scripts

### Security & Vulnerability Management

- **[CVE-2025-59287.ps1](CVE-2025-59287.ps1)** - Scan Active Directory for WSUS servers potentially vulnerable to CVE-2025-59287

### Network & Connectivity

- **[Check-Open-Ports.ps1](Check-Open-Ports.ps1)** - Monitor active TCP connections with process details and data transfer statistics
- **[Get-ActiveConnections.ps1](Get-ActiveConnections.ps1)** - Display established network connections with process information
- **[network-bandwidth.ps1](network-bandwidth.ps1)** - Test network bandwidth using CacheFly CDN (Atera RMM compatible)

### System Maintenance

- **[Giphy-Cleanup.ps1](Giphy-Cleanup.ps1)** - Clean up Zoom processes and Giphy cache data (optimized for Azure Virtual Desktop)

## 💻 Usage

Most scripts can be executed directly without parameters:

```powershell
.\ScriptName.ps1
```

Some scripts support additional parameters for enhanced functionality:

```powershell
.\CVE-2025-59287.ps1 -ScanAllServers -VerboseOutput -OutputPath "C:\Temp\results.csv"
```

Some scripts may require administrative privileges for full functionality. Check individual script documentation for specific requirements.

## 📖 Documentation

Each script includes comprehensive inline documentation with:
- Synopsis and detailed description
- Parameter information
- Usage examples
- Author and notes

View help for any script using:

```powershell
Get-Help .\ScriptName.ps1 -Full
```

## ⚙️ Requirements

- Windows PowerShell 5.1 or PowerShell 7+
- Administrative privileges may be required for certain scripts
- Active Directory module (for AD-related scripts)
- Internet connectivity for network testing utilities

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**handcaster** - [neu-sec](https://github.com/neu-sec)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

---

*This repository is actively maintained and regularly updated with new utilities.*