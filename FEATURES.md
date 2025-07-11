## Features <!-- markdown-link-check-disable-next-line -->

- Uses OpenAI's [Completion API](https://api.openai.com/v1/chat/completions).
- Responses are returned in [stream mode](https://platform.openai.com/docs/api-reference/chat/create#stream) as they are generated by OpenAI.
- Conversation style is like ChatGPT.
- Multiple languages supported:
  - Deutsch,
    Ελληνικά,
    English,
    Español,
    Français,
    हिन्दी,
    Bahasa Indonesia,
    Italiano,
    日本語,
    한국어,
    Polski,
    Русский,
    Svenska,
    ไทย,
    Tiếng Việt,
    中文
- Can select which model to use, like gpt-3.5-turbo, gpt-4.
  - Model context window and knowledge cutoff date are shown.
  * Note: If you don't see gpt-4 listed in the model selector, then you don't have access. GPT-4 API access is currently accessible to those who have made at least [one successful payment](https://help.openai.com/en/articles/7102672-how-can-i-access-gpt-4) through the OpenAI developer platform.
- Markdown formatting
- Syntax highlighting of code responses
- Conversation History Sidebar
  - History of conversations is stored locally using the browser's IndexedDB API.
  - Group conversations by Today, Yesterday, Last Week, Last Month.
  - Search conversations by searching for substrings in title.
  - Edit conversation title.
- Handles error conditions
  - Exceeding token limit for selected model.
- System prompt to give instructions.
- Set your OpenAI API key in local.env.json
