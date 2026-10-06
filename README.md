# dns-policy

Персональные DNS-списки для AdGuard Home: блокировка рекламы, трекеров и телеметрии. Репозиторий предназначен для личного использования. Содержимое, структура и ссылки на файлы могут изменяться или удаляться без предварительного уведомления.

| Файл | Содержимое |
|---|---|
| [allow-global.txt](https://raw.githubusercontent.com/thisnamebusy/dns-policy/main/allow-global.txt) | Разрешённые домены |
| [deny-global.txt](https://raw.githubusercontent.com/thisnamebusy/dns-policy/main/deny-global.txt) | Дополнительные блокировки |
| [deny-ps4.txt](https://raw.githubusercontent.com/thisnamebusy/dns-policy/main/deny-ps4.txt) | Ограничения обновлений и сервисов PS4 |
| [hblock-hosts.txt](https://raw.githubusercontent.com/thisnamebusy/dns-policy/main/hblock-hosts.txt) | Зеркало [hBlock](https://github.com/hectorm/hblock): реклама, трекеры и вредоносные домены |

Ссылки ведут непосредственно на файлы для подключения в AdGuard Home. `allow-global.txt` используется как белый список, остальные — как чёрные.

Зеркало hBlock обновляется через GitHub Actions ежедневно в **00:30 по Москве**. При неудачной загрузке сохраняется предыдущая версия. Собственные списки редактируются вручную.
