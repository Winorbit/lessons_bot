## Продолжаем наращивать новый функционал на нашего бота, практикуясь с имеющимися навыками

Добавлен функционал, который позволяет получать данные о погоде.
Запуск бота вынесен в отдельный файл - теперь логика лежит отдельно, а управление ею, (пока на уровне включить/выключить) отдельно.

Добавлена возможность ответа на команды:
```bash
/weather <city>
например
/weather Lviv

```

### Подготовка и запуск
pip install requests

```bash
python run.py

```
или

```bash
python3 run.py
```
