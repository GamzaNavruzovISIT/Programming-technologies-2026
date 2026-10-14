# Programming-technologies-2026

![Трон](https://i.redd.it/8anal7f5vqm41.png)

Greetings, programs!

Это репозиторий для курса "Технологии программирования" в 2026-2027 учебном году.

## Структура репозитория

- [assets](assets) - папка с различными демонстрационными материалами;
- [labs](labs) - папка с лабораторными работами;
- [students](students) - папка с отчетами студентов.


# Как работаем

Первым делом форкните репозиторий и клонируйте его на ваш компьютер.
```bash
git clone <url-вашего-форка>
```

Затем создайте ветку для вашей лабораторной работы.
```bash
git checkout -b <имя-ветки>
```

Выполните лабораторную работу и сохраните результаты в файл `reportL<номер-лабораторной-работы>.md`.
```bash
echo "<ваш-ответ>" > reportL<номер-лабораторной-работы>.md
```

Затем отправьте ваш ответ в репозиторий.
```bash
git add reportL<номер-лабораторной-работы>.md
git commit -m "Добавлен ответ на лабораторную работу <номер-лабораторной-работы>"
git push origin <имя-ветки>
```

Затем создайте pull request в основной репозиторий.
```bash
git pull origin main
git push origin <имя-ветки>
```

После этого начинается очная защита лабораторной работы. Полагаю, что вы уже знаете, как это делается:)

# Различные полезные ссылки

- [OpenAI API](https://platform.openai.com/docs/api-reference)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
- [Mistral](https://mistral.ai/)
- [DeepSeek](https://deepseek.com/)
- [LangChain](https://langchain.com/)
- [LlamaIndex](https://www.llamaindex.ai/)
- [Hugging Face](https://huggingface.co/)