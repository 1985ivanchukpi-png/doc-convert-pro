# doc-convert pro 🚀

**doc-convert pro** — профессиональная система OCR и конвертации документов в Docker.

## 🌟 Возможности
* **OCR:** RU, UA, EN, DE, PL, PT.
* **Форматы:** PDF, DOCX, TXT.
* **Интерфейс:** 3 колонки (5% / 40% / 55%).

## 🚀 Запуск
```bash
docker build --no-cache -t doc_project_img .
docker run -d --name doc_converter_prod -p 8502:8502 -v $(pwd)/static:/app/static doc_project_img
