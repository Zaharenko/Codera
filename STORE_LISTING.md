# Chrome Web Store — CodeRa listing copy
Prepared 8 Oct 2026 · Paste into Developer Dashboard

## Name (≤75)
CodeRa: Copy Code from Video & Image (YouTube, Udemy)

## Summary (≤132)
Copy code from YouTube, Udemy & Coursera videos in 1 click. AI OCR keeps indentation. Free, no sign-up.

## Category
Developer Tools

## Support URL
https://codera.click/changelog.html

## Website
https://codera.click/

## Full description (English)

Stop pausing tutorials to retype code. CodeRa copies code from YouTube, Udemy and Coursera videos, screenshots and images in one click, with indentation, brackets and comments intact.

HOW IT WORKS
1. Open any coding video or page.
2. Press Alt+C, click the floating CodeRa button, or drag to select an area. The video keeps playing.
3. Formatted code lands in your clipboard in a few seconds. Paste it into VS Code, Cursor or any editor.

THREE MODES
• Extract as code: AI reads the frame and keeps indentation, brackets, semicolons and comments.
• Plain text: subtitles, slide text, diagrams and UI labels exactly as shown.
• Understand code: explains what a snippet does, traces it line by line and shows the expected output.

MORE FEATURES (rolling out in v1.2.0)
• Collect whole lesson: keep watching while CodeRa gathers frames, then get a timestamped timeline and assembled project files.
• Local snippet library with search, filters and timestamps. It stays in your browser.
• Export to Obsidian, Notion (Markdown), Anki and GitLab Snippets, only when you press export.
• Bracket check that flags likely OCR mistakes before you paste.
• Ask follow-up questions about a snippet or convert it to another language.

WORKS ON
YouTube (including live streams), Udemy, Coursera, Skillshare, conference talks, Zoom and Meet shares, PDFs, slides, Slack and Discord screenshots, and image-only code blocks in documentation.

WHY NOT GOOGLE LENS OR A CHATBOT?
General OCR often flattens indentation and confuses symbols like { } => ;. Chatbots can fix formatting, but need several steps: screenshot, upload, prompt, copy. CodeRa is built for code and does it in one click without leaving the page.

PRIVACY, PLAIN AND SIMPLE
• No account needed.
• CodeRa does not keep your screenshots or build a cloud library. Your snippet library stays in your browser.
• When you extract, the image is sent through a CodeRa relay to Anthropic's Claude API for processing. Under Anthropic's commercial terms, customer content is not used to train models by default.
• Do not capture passwords, keys or confidential material, and do not use CodeRa on code your employer forbids sending to third-party AI services.
• Details: https://codera.click/privacy.html

FREE DURING EARLY ACCESS
All features are unlocked while CodeRa is in early access. Fair-use limits may apply. Feedback is welcome: hello@codera.click

CodeRa is an independent product, not affiliated with or endorsed by Anthropic. You are responsible for following the terms of the sites whose content you capture.

## Full description (Русский)

Хватит ставить уроки на паузу и перепечатывать код. CodeRa копирует код с видео YouTube, Udemy и Coursera, со скриншотов и картинок в один клик: с отступами, скобками и комментариями.

КАК ЭТО РАБОТАЕТ
1. Откройте любое видео или страницу с кодом.
2. Нажмите Alt+C, плавающую кнопку CodeRa или выделите область. Видео продолжает играть.
3. Готовый код через несколько секунд окажется в буфере обмена. Вставьте его в VS Code, Cursor или любой редактор.

ТРИ РЕЖИМА
• Код: ИИ читает кадр и сохраняет отступы, скобки, точки с запятой и комментарии.
• Текст: субтитры, слайды, схемы и подписи интерфейса как есть.
• Объяснение: что делает фрагмент, разбор по строкам и ожидаемый результат.

ЕЩЁ (появляется в версии 1.2.0)
• Сбор всего урока: смотрите дальше, а CodeRa собирает кадры и выдаёт таймлайн и файлы проекта.
• Локальная библиотека сниппетов с поиском и фильтрами. Хранится в вашем браузере.
• Экспорт в Obsidian, Notion (Markdown), Anki и GitLab Snippets только по нажатию кнопки.
• Проверка скобок: подсвечивает вероятные ошибки распознавания.
• Вопросы по сниппету и конвертация в другой язык.

ГДЕ РАБОТАЕТ
YouTube (в том числе стримы), Udemy, Coursera, Skillshare, доклады с конференций, демонстрации экрана в Zoom и Meet, PDF, слайды, скриншоты из Slack и Discord, документация с кодом в картинках.

ПРИВАТНОСТЬ
• Аккаунт не нужен.
• CodeRa не хранит ваши скриншоты и не ведёт облачную библиотеку. Библиотека сниппетов остаётся в браузере.
• При распознавании изображение передаётся через релей CodeRa в API Claude (Anthropic). По коммерческим условиям Anthropic данные клиентов API по умолчанию не используются для обучения моделей.
• Не снимайте пароли, ключи и конфиденциальные материалы. Не используйте CodeRa для кода, который работодатель запрещает отправлять во внешние ИИ-сервисы.
• Подробности: https://codera.click/privacy.html

БЕСПЛАТНО В РАННЕМ ДОСТУПЕ
Все функции открыты. Могут действовать лимиты добросовестного использования. Отзывы и идеи: hello@codera.click

CodeRa — независимый продукт и не связан с Anthropic. Вы сами отвечаете за соблюдение правил сайтов, контент которых снимаете.

## Privacy tab (Dashboard notes)

- Single purpose: Extract text and code from images and video frames the user selects, and copy the result to the clipboard.
- Data type: Website content (images/frames and text of the area the user captures). Used only for the core feature. Not sold. Review whether Authentication information also applies (optional API keys / export tokens stored locally).
- activeTab: access the current tab when the user starts a capture.
- scripting: inject the selection overlay, floating button, hotkey handler and toasts.
- clipboardWrite: copy extracted code or text to the clipboard.
- storage: save preferences, the local snippet library and optional keys or tokens in the browser.
- Host permissions (from manifest): `<all_urls>`, `https://codera.click/*` (relay and site).
- Remote code: none (confirm in package).

## Screenshot captions (1280×800)

1. Copy code from any video in 1 click
2. Indentation preserved
3. Works while the video plays
4. Collect a whole lesson into project files (1.2.0)
5. Understand mode: explain and trace
