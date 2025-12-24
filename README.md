# dns-allowlists

Централизованные DNS списки для локальной инфраструктуры (AdGuard Home).

## Назначение

Репозиторий содержит списки доменов, которые должны быть **разрешены** при использовании DNS-фильтрации чёрных списков.

Формат списков: **один домен на строку** (FQDN), без AdBlock-синтаксиса.

Примеры корректных строк:
- `example.com`
- `api.example.com`

## Файлы

- `allow-global.txt` — глобальный allowlist.
- `allow-jellyfin.txt` — allowlist для клиента/сервиса Jellyfin.
- `allow-ps5.txt` — allowlist для PlayStation 5.
- `allow-smb.txt` — allowlist для SMB/torrent-клиента.
- `deny-global.txt` — глобальный denylist.
