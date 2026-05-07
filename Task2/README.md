# Task2 — Проектирование решения (Privacy by Design)

## Что сделано

- `source/Task2/c4-context-to-be.md` — **C4 Context** (To‑Be) в Markdown (Mermaid) + пояснение новых блоков Privacy by Design.
- `source/Task2/c4-container-to-be.md` — **C4 Container** (To‑Be) в Markdown (Mermaid).
- `c4-context-to-be.drawio.xml` — C4 Context (To‑Be) в формате **draw.io**.
- `c4-container-to-be.drawio.xml` — C4 Container (To‑Be) в формате **draw.io**.
- `analytics-layer.md` — целевой **аналитический слой** (Lakehouse/BI/ML/AI) с обезличиванием, тегированием, lineage и контролем доступа.

## Ключевая идея

Перенести данные из «файлов рядом с пользователем» в управляемые домены и сервисы, где:
- доступ выдаётся **к данным**, а не к «общей папке»;
- соблюдаются **минимизация**, **разделение доменов**, **аудит**, **шифрование**, **тегирование**;
- для аналитики используется **обезличенный/псевдонимизированный** слой с управлением ключами и lineage.
