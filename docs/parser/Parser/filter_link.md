### filter_link(self, link_url: str) -> bool
Фильтрует ссылку. Если ссылка является файлом разметки, не является
POST запросом и не является игнорируемой ссылкой, то возвращает True, иначе
False.