# DS4AudioStreamer — сборка через GitHub Actions

Стриминг звука с ПК на наушники/динамик DualShock 4 по USB или Bluetooth.

## Как собрать .exe

Сборка происходит автоматически на GitHub, вручную ничего ставить не нужно.

1. Перейди во вкладку **Actions**.
2. Открой workflow **Build DS4AudioStreamer.exe**.
3. Нажми **Run workflow** → **Run workflow**.
4. Дождись зелёной галочки (1–3 минуты).
5. Открой завершённый запуск, внизу в разделе **Artifacts** скачай **DS4AudioStreamer-exe**.

Внутри архива:
- `DS4AudioStreamer.exe`
- `libsbc.dll`
- `libsamplerate-0.dll`

Все три файла должны лежать в одной папке при запуске.

## Запуск

Просто запусти `DS4AudioStreamer.exe`. Если Windows покажет предупреждение SmartScreen (сборка не подписана) — нажми **Подробнее** → **Выполнить в любом случае**.
