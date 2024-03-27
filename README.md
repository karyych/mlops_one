### `README.md`

В данном файле описывается методология ведения репозитория.

```markdown
## Методология ведения репозитория

В этом разделе описывается методология ведения репозитория, используемая в проекте.

### Ветки

Используются следующие ветки для разработки:
- 'main': ветка, содержащая стабильную версию проекта
- 'back': ветка для разработки новых функций и исправлений.

### Ревью кода

Все изменения, вносимые в проект, проходят код-ревью перед слиянием в основную ветку.

### Pull Requests

Для внесения изменений в проект создайте новый Pull Request из вашей ветки в ветку 'back'. Убедитесь, что код соответсвует принятым стандартам, и оставьте подробное описание изменений.

### Требования к Merge Requests

- Все Pull Request должны быть связаны с Issue, описывающим необходимость изменений.
- Каждый Pull Request должен успешно пройти проверку линтеров и тестов перед слиянием.

Эти правила помогают поддерживать стабильность и качество кода в проекте.
