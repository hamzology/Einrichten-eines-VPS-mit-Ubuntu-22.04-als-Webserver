Here is the content formatted in proper Markdown syntax for GitHub:

```markdown
# VPS Setup Guide

## Wir werden behandeln

### VPS-Setup:
- Installieren und Konfigurieren des Servers mit Ubuntu als Betriebssystem.

### Erforderliche Softwareinstallation:
- Einrichten und Konfigurieren von Nginx als Webserver.
- Installieren und Konfigurieren von PHP (8.3 empfohlen) mit allen notwendigen Erweiterungen, um die Anforderungen sowohl für WoltLab als auch für XenForo zu erfüllen.
- Installieren und Konfigurieren von MariaDB, um die Kompatibilität mit beiden Anwendungen sicherzustellen.

### phpMyAdmin-Installation:
- Installieren und Konfigurieren von phpMyAdmin zur Datenbankverwaltung.

### Domain-Konfiguration:
- Den Domainnamen `cyber-usenet.eu` mit dem Server verbinden.
- SSL für die Domain einrichten, um sichere HTTPS-Verbindungen zu ermöglichen.

### Server-Sicherheit:
- Beste Praktiken zur Härtung des Servers umsetzen, einschließlich der Konfiguration der Firewall und der Installation von fail2ban.

Dieser Leitfaden ist speziell für Ubuntu 22.04 entwickelt, sollte jedoch auch auf neueren Ubuntu-Versionen mit minimalen Anpassungen funktionieren. Jeder Schritt wird mit Befehlen und deren Zwecken erklärt, um Klarheit und eine einfache Umsetzung zu gewährleisten.

> **Hinweis:** Um die Ausgaben der ausgeführten Befehle zu sehen, klicken Sie auf den `<ref>`-Link jedes Befehls.

---

## Erste VPS-Einrichtung

### 1. System aktualisieren und upgraden
```bash
sudo apt update && sudo apt upgrade -y
```
(Dies stellt sicher, dass Ihr System die neuesten Software-Updates und Sicherheitspatches enthält.) `<ref>`

### 2. Erforderliche Tools installieren
```bash
sudo apt install -y curl wget unzip gnupg nano software-properties-common
```
(Installieren Sie wichtige Dienstprogramme zur Verwaltung Ihres Servers.) `<ref>`
```

This Markdown structure organizes the content clearly with proper headers, subheaders, and code blocks. Let me know if you need further adjustments or additions!
