# Densory Backups — Konfiguration

Die folgenden Einstellungen stehen für dieses Produkt zur Verfügung:

Alle folgenden Einstellungen konfigurierst du in deinem [Control Center](https://densory.com/dashboard).

| Key | Typ | Default | Beschreibung |
| --- | --- | --- | --- |
| `locale` | `string` | `""` | Sprache |
| `default_color` | `hexColor` | `#444444` | Standardfarbe |
| `success_color` | `hexColor` | `#2bfc71` | Erfolgsfarbe |
| `warning_color` | `hexColor` | `#ffd621` | Warnfarbe |
| `error_color` | `hexColor` | `#fc251e` | Fehlerfarbe |
| `success_img` | `image` | `/uploads/assets/product-images/discord-bots/default/success.png` | Erfolgsbild |
| `warning_img` | `image` | `/uploads/assets/product-images/discord-bots/default/warning.png` | Warnbild |
| `error_img` | `image` | `/uploads/assets/product-images/discord-bots/default/error.png` | Fehlerbild |
| `backup_channels` | `channels` | `[]` | Backup-Kanäle |
| `backup_interval` | `string` | `daily` | Backup-Intervall |
| `log_channel` | `channel` | `""` | Log Kanal |
| `max_messages` | `number` | `5000` | Max. Nachrichten pro Backup |
| `max_file_size` | `string` | `10` | Max. Dateigröße |
