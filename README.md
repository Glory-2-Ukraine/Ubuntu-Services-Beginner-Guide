# Ubuntu Services Beginner Guide
## Посібник для початківців: Служби в Ubuntu

A complete beginner's guide to running applications as background services in Ubuntu 24.04 using systemd.

Повний посібник для початківців з запуску застосунків як фонових служб в Ubuntu 24.04 за допомогою systemd.

---

## Contents / Зміст

| File | Description |
|------|-------------|
| `Ubuntu_Services_Guide_EN_UK.docx` | Full bilingual guide (English + Ukrainian) — Word document |

---

## What's Inside / Що всередині

The guide covers / Посібник охоплює:

1. **What systemd is** / Що таке systemd
2. **Opening a Terminal** / Відкриття Термінала
3. **Creating a service file** (step-by-step) / Створення файлу служби
4. **Enabling and starting your service** / Увімкнення та запуск служби
5. **Checking service status** / Перевірка стану служби
6. **Common management commands** / Основні команди управління
7. **Troubleshooting** / Вирішення проблем
8. **Removing a service** / Видалення служби

---

## Quick Reference / Швидкий довідник

```bash
# Create service file
sudo nano /etc/systemd/system/myapp.service

# Reload, enable, and start
sudo systemctl daemon-reload
sudo systemctl enable myapp.service
sudo systemctl start myapp.service

# Check status
sudo systemctl status myapp.service

# View logs
journalctl -u myapp.service -f
```

---

*Part of the [Glory-2-Ukraine](https://github.com/Glory-2-Ukraine) infrastructure toolkit.*
