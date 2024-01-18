# IPUpdate

Update dynamic white ip address in **RDCMan** via **Discord**.

## EN

- Need to create a [bot](https://discord.com/developers/applications) and Discord server, get bot token and channel id on the server. \
- Update variables: `DISCORD_TOKEN`, `DISCORD_CHANNEL_ID`, `RDCMan_RDG_PATH` (path to configuration file) and `RDCMan_Display_Name` (server name in configuration). \
- Run `Send-IpToDiscord.ps1` to send your IP address to the Discord channel (it checks the last message and only sends a message if the address has changed). \
- Run `Write-IpToRDCMan.ps1` on the remote computer to update the address in the configuration (reads the latest IP address from Discord and updates only if the IP address is different from the configured one).

## RU

- Необходимо создать [бота](https://discord.com/developers/applications) и сервер Discord, получить токен бота и id канала на сервере. \
- Обновите переменные: `DISCORD_TOKEN`, `DISCORD_CHANNEL_ID`, `RDCMan_RDG_PATH` (путь до файла конфигурации) and  `RDCMan_Display_Name` (имя сервера в конфигурации). \
- Запустите `Send-IpToDiscord.ps1` что бы отправить свой IP-адрес в Discord канал (проверяет последнее сообщение и только в случае смены адреса отправляет сообщение). \
- Запустите `Write-IpToRDCMan.ps1` на удаленном компьютере, что бы обновить адрес в конфигурации (читает последний IP-адрес из Discord и обновляет только если IP-адрес отличается от настроенного в конфигурации).
