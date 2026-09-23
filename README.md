# Програма на Ема

Готово PWA приложение за GitHub Pages.

## Публикуване
1. Създайте публично GitHub repository, например `ema-timetable`.
2. Качете съдържанието на тази папка директно в основната директория на repository.
3. Отворете **Settings → Pages**.
4. Изберете **Deploy from a branch**, branch **main**, folder **/(root)** и натиснете **Save**.
5. След публикуване отворете адреса в Safari на iPhone и изберете **Share → Add to Home Screen**.

## Обновяване
- Разписание: `schedule.json`
- Календар на МОН: `calendar.json`
- При промени сменете стойността `ema-v3` в `service-worker.js`, например на `ema-v4`, за да се обнови офлайн кешът.
