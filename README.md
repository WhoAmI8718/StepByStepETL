# StepByStepETL

Учебный ETL-проект, создаваемый с нуля без оркестратора.

## Цель

Построить pipeline:

CSV → extract → transform → validate → load → PostgreSQL

## Текущий этап

Настройка структуры Python-проекта, Git и тестового окружения.

## Подготовка окружения

Создать виртуальное окружение:

```powershell
python -m venv .venv
```

Активировать его:

```powershell
.\.venv\Scripts\Activate.ps1
```

Установить инструменты разработки:

```powershell
python -m pip install -r requirements-dev.txt
```