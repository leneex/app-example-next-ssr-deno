# Next.js на Deno

Пример приложения [Next.js](https://nextjs.org/) на [Deno](https://deno.com/) с серверным рендерингом (SSR).

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **Next.js** и тип приложения **backend**. Приложение запускается как сервер.

| Параметр | Значение |
| --- | --- |
| Фреймворк | Next.js |
| Версия Deno | 2.7.14 |
| Тип приложения | `backend` |
| Команда сборки | `deno task build` |
| Команда запуска | `deno task start` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build

# запуск собранного серверного приложения
deno task start
```
