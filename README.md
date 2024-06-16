# Автотесты для личного кабинета агента

## Полезные команды
1. Команда для тестового запуска и отладки функций из файла utils.ts (лн лежит в папке tests) в терминале
npx ts-node tests/utils.ts
2. Импортирует написанные функции из файла utils.ts в файл тестов
import * as utils from './utils.ts'
3. Команда для запуска тестов с визуальным представлением
npx playwright test LKAtest1.spec.ts --ui
4. Команда в Терминале для запуска декодера для записи теста с фронта
npx playwright codegen "тут урл страницы для теста без скобок"

## Работа с GIT

### Настроить локальный репозиторий
```bash
git clone git@github.com:SealTania/Autotest_LKA.git
cd Autotest_LKA
npm install
```
