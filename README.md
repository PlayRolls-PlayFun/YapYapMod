# YapYap Console Mod

[English](#english) | [Русский](#russian)

---

<a name="english"></a>
## 🇬🇧 English

### Description
A console mod for YAPYAP that allows you to use cheat commands in-game. Perfect for testing magic on monsters without grinding for gold!

### Features
- 💰 Add gold instantly
- 🔍 Search game classes and methods
- 📝 Export console output to file
- 🎮 Works in multiplayer (shared balance)
- ⌨️ Easy to use console interface

### Requirements
- **BepInEx 5.x** - [Download here](https://github.com/BepInEx/BepInEx/releases)
- YAPYAP game (Steam version)

### Installation

1. **Install BepInEx:**
   - Download BepInEx 5.x from the link above
   - Extract the archive to your game folder
   - Run the game once to generate folders

2. **Install the mod:**
   - Copy `YapYapConsoleMod.dll` to `BepInEx/plugins/`
   - That's it!

### Usage

1. Launch the game
2. Press **ESC** to unlock cursor (open game menu)
3. Press **F1** to open the console
4. Type a command and press Enter

### Commands

| Command | Description | Example |
|---------|-------------|---------|
| `money <amount>` | Add gold | `money 1000` |
| `find <text>` | Search for classes | `find player` |
| `listkeys` | Show all save data keys | `listkeys` |
| `debug` | Show SaveManager methods | `debug` |
| `export` | Save console output to file | `export` |
| `clear` | Clear console | `clear` |
| `help` | Show help | `help` |

### Notes

- **GUI Update:** The gold counter updates when you buy something or pick up a coin
- **Multiplayer:** Works perfectly! Gold is shared between all players
- **Console Output:** Exported to `BepInEx/console_output.txt`

### Troubleshooting

**Console doesn't open:**
- Make sure BepInEx is installed correctly
- Check logs in `BepInEx/LogOutput.log`
- Try a different key in config: `BepInEx/config/com.yourname.yapyap.consolemod.cfg`

**Money command doesn't work:**
- Make sure you're in-game (not in menu)
- Check the console output for errors
- Try the `debug` command to see if GameManager is found

### Credits
Created with ❤️ for the YAPYAP community

---

<a name="russian"></a>
## 🇷🇺 Русский

### Описание
Мод-консоль для YAPYAP, позволяющий использовать чит-команды в игре. Идеально подходит для тестирования магии на монстрах без фарма золота!

### Возможности
- 💰 Мгновенное добавление золота
- 🔍 Поиск классов и методов игры
- 📝 Экспорт вывода консоли в файл
- 🎮 Работает в мультиплеере (общий баланс)
- ⌨️ Удобный интерфейс консоли

### Требования
- **BepInEx 5.x** - [Скачать здесь](https://github.com/BepInEx/BepInEx/releases)
- Игра YAPYAP (Steam версия)

### Установка

1. **Установите BepInEx:**
   - Скачайте BepInEx 5.x по ссылке выше
   - Распакуйте архив в папку с игрой
   - Запустите игру один раз для создания папок

2. **Установите мод:**
   - Скопируйте `YapYapConsoleMod.dll` в `BepInEx/plugins/`
   - Готово!

### Использование

1. Запустите игру
2. Нажмите **ESC** чтобы разблокировать курсор (открыть меню)
3. Нажмите **F1** для открытия консоли
4. Введите команду и нажмите Enter

### Команды

| Команда | Описание | Пример |
|---------|----------|--------|
| `money <количество>` | Добавить золото | `money 1000` |
| `find <текст>` | Поиск классов | `find player` |
| `listkeys` | Показать все ключи сохранения | `listkeys` |
| `debug` | Показать методы SaveManager | `debug` |
| `export` | Сохранить вывод консоли в файл | `export` |
| `clear` | Очистить консоль | `clear` |
| `help` | Показать справку | `help` |

### Примечания

- **Обновление GUI:** Счетчик золота обновляется при покупке или подборе монеты
- **Мультиплеер:** Работает отлично! Золото общее для всех игроков
- **Вывод консоли:** Экспортируется в `BepInEx/console_output.txt`

### Решение проблем

**Консоль не открывается:**
- Убедитесь что BepInEx установлен правильно
- Проверьте логи в `BepInEx/LogOutput.log`
- Попробуйте другую клавишу в конфиге: `BepInEx/config/com.yourname.yapyap.consolemod.cfg`

**Команда money не работает:**
- Убедитесь что вы в игре (не в меню)
- Проверьте вывод консоли на ошибки
- Попробуйте команду `debug` чтобы проверить найден ли GameManager

### Благодарности
Создано с ❤️ для сообщества YAPYAP

---

## 📝 License
Free to use and modify. Share with friends!

## 🐛 Bug Reports
If you find any bugs, please report them in the comments or create an issue.

## 💡 Future Features
- God mode
- Speed multiplier
- Spawn items
- Teleport commands

Enjoy the mod! 🎮✨
