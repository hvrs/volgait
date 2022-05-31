# volgait
## Перед началом
Удалите папку "Migrations" и создайте новые миграции:
Откройте консоль диспетчера пакетов(Сервис - Диспетчер пакетов NuGet - Консоль диспетчера пакетов):
PM>Add-Migration
PM> Update-Database
### Обновить строки в appsettings.json, Views/Home/ListApplication.cshtml, Views/Home/DB.cs
string connectionString = "Host=localhost;Username=postgres;Password='password';Database=database_name";
