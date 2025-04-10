# GPT-4 Tarot Bot 🔮🤖

Интеллектуальный Telegram-бот для раскладов Таро с использованием GPT-4 и DeepSeek. Проект ориентирован на монетизацию через подписку и качественную работу с изображениями и текстовыми запросами.

---

## 🧠 Описание

Бот позволяет пользователю получать **расклады Таро** как по текстовому описанию запроса, так и по отправленным фотографиям карт. При этом:

- Текстовые запросы обрабатываются через **DeepSeek**
- Фото-запросы — через **GPT-4 Vision** (для повышения качества и экономии средств)

Также реализовано:

- 📋 **История общения** — сохранение и сжатие предыдущих сообщений для формирования контекста
- 🛠 **Админ-панель** — для управления подписками, логами и пользователями, рассылками и блокировками
![image](https://github.com/user-attachments/assets/88d0e63b-691d-4141-9fbc-a831ed56e770)
![image](https://github.com/user-attachments/assets/b1ca0c72-7456-4155-85ca-8ba39bc8f8c4)


- 📸 **Фотообработка** — поддержка изображений и работа с визуальным контекстом
- 🧾 **Логирование** — действия пользователя записываются в отдельный Telegram-канал
- 🔐 **Доступ только по подписке** в указанный Telegram-канал

---

## ⚙️ Технологии

| Технология      | Назначение                                      |
|------------------|-------------------------------------------------|
| Node.js          | Бэкенд-логика                                   |
| Telegram Bot API | Общение с пользователем                         |
| SQLite + Sequelize | Хранение пользователей, истории, подписок     |
| OpenAI API       | GPT-4 Vision для обработки фото                 |
| DeepSeek API     | Обработка текстовых запросов                    |
| Telegram Channel | Логирование всех действий                       |

---
