# ChatGPT Телеграм бот теперь на русском: **GPT-4. Быстрый. Без ежедневных лимитов. Специальные режимы чата**

<div align="center">
<img src="https://raw.githubusercontent.com/karfly/chatgpt_telegram_bot/main/static/header.png" align="center" style="width: 100%" />
</div>

<br>

Мы все любим [chat.openai.com](https://chat.openai.com), но... Он УЖАСНО лагает, имеет ежедневные ограничения и доступен только через архаичный веб-интерфейс.

Это репо - ChatGPT, переделанный под Telegram Bot. **И он отлично работает.**

Вы можете установить своего собственного бота или использовать моего: [@chatgpt_karfly_bot](https://t.me/chatgpt_karfly_bot)

## Особенности
- Ответы с низкой задержкой (обычно это занимает около 3-5 секунд)
- Нет ограничений на запросы
- Потоковая передача сообщений (смотрите демо)
- Поддержка GPT-4
- Поддержка группового чата (/help_group_chat для получения инструкций)
- DALLE 2 (выберите режим 👩‍🎨 Artist для создания изображений)
- Распознавание голосовых сообщений
- Выделение кода
- 15 специальных режимов чата: 👩🏼‍🎓 Assistant, 👩🏼‍💻 Code Assistant, 👩‍🎨 Artist, 🧠 Psychologist, 🚀 Elon Musk и другие. Вы можете легко создать свои собственные режимы чата, отредактировав `config/chat_modes.yml`.
- Поддержка [ChatGPT API](https://platform.openai.com/docs/guides/chat/introduction)
- Список разрешенных пользователей Telegram
- Отслеживание $ баланса, потраченного на OpenAI API



<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmM2ZWVjY2M4NWQ3ZThkYmQ3MDhmMTEzZGUwOGFmOThlMDIzZGM4YiZjdD1n/unx907h7GSiLAugzVX/giphy.gif" />
</p>

---

## Установка

1. Получите ключ [OpenAI API](https://openai.com/api/).

2. Получите токен бота Telegram от [@BotFather](https://t.me/BotFather).

3. Отредактируйте `config/config.example.yml` для установки токенов и выполните 2 команды ниже (*если вы продвинутый пользователь, вы также можете отредактировать* `config/config.example.env`):
    ``bash
    mv config/config.example.yml config/config.yml
    mv config/config.example.env config/config.env
    ```

4. 🔥 А теперь **запустите**:
    ``bash
    docker-compose --env-file config/config.env up --build

    
## Ссылки

1. [*Сборка ChatGPT из GPT-3*](https://learnprompting.org/docs/applied_prompting/build_chatgpt)

