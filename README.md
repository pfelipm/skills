# 🛠️ Gemini CLI Skills

Este repositorio contiene una colección de skills (habilidades) especializadas para potenciar las capacidades de **Gemini CLI**.

## 🧰 Skills disponibles

### 🚀 [gas-web-expert](./gas-web-expert)
Consultor senior para la creación de aplicaciones web multiusuario en Google Workspace, optimizadas para desarrollo local con `clasp` e integración con Google Sheets.

#### Instalación directa
```bash
gemini skills install https://github.com/pfelipm/skills.git --path gas-web-expert
```

---

## 📥 Cómo instalar una skill

Puedes instalar las skills de este repositorio de dos formas:

### 1. Desde la URL del repositorio (Recomendado)
Usa el flag `--path` para apuntar a la carpeta de la skill específica:

```bash
gemini skills install https://github.com/pfelipm/skills.git --path NOMBRE_DE_LA_SKILL
```

### 2. Desde un archivo `.skill`
Si has descargado el archivo empaquetado desde la sección de [Releases](https://github.com/pfelipm/skills/releases):

```bash
gemini skills install ./nombre-de-la-skill.skill
```

## 🏗️ Cómo contribuir
Si quieres añadir una nueva skill a este monorepo:
1. Crea una nueva carpeta con el nombre de tu skill.
2. Asegúrate de incluir un archivo `SKILL.md` con la definición de la habilidad.
3. Sigue la estructura de carpetas: `assets/`, `references/` y `scripts/`.

---
Creado por [pfelipm](https://github.com/pfelipm)
