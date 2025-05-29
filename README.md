
# Generador de Backend
🎯 **shqmv-backend-gen** es una herramienta de línea de comandos que permite generar rápidamente plantillas de backend con tecnologías modernas como FastAPI, SQLAlchemy y Docker, ideal para acelerar el desarrollo de APIs RESTful y microservicios en Python.


## 🚀 Instalación
Puedes instalar el generador directamente desde PyPI:
```bash
pip install shqmv-backend-gen
```

## ⚙️ Uso
Inicializa un nuevo proyecto con el stack que prefieras mediante el comando:
```bash
shqmv-backend-gen init project-name
```
Esto abrirá un menú interactivo donde podrás elegir entre distintos stacks disponibles (**por ejemplo:** FastAPI + SQLAlchemy) y generar tu plantilla con la estructura lista para empezar a trabajar.

## 📁 Estructura generada
Un ejemplo del stack **FastAPI + SQLAlchemy** genera una estructura como esta:

```bash
project-name/
├── app/
│   ├── main.py
│   ├── models/
│   └── routes/
├── requirements.txt
└── .env
```

| Tipo           | Tecnologías                |
|----------------|----------------------------|
| ✅ **Base**        | - FastAPI                  |
| ✅ **Complemento** | - SQLAlchemy<br> - OAuth2 + JWT |

## 👨‍💻 Autor
Desarrollado por [**shqmv**](https://github.com/shqmv)

Contacto: **shaquille.montero.vergel123@gmail.com**
