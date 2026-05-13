# 🛠️ Gemini CLI Skills

Este repositorio contiene una colección de skills (habilidades) especializadas para potenciar las capacidades de **Gemini CLI**.

## 🧰 Skills disponibles

### 🚀 [gas-web-expert](./gas-web-expert)
Consultor senior para la creación de aplicaciones web multiusuario en Google Workspace, optimizadas para desarrollo local con `clasp` e integración con Google Sheets.

#### Instalación directa
```bash
gemini skills install https://github.com/pfelipm/skills --path gas-web-expert
```

---

## 📥 Cómo instalar una skill

Puedes instalar las skills de este repositorio usando la URL del repositorio y el flag `--path` para indicar la carpeta de la skill:

```bash
gemini skills install https://github.com/pfelipm/skills --path NOMBRE_DE_LA_SKILL
```

Si prefieres descargar el archivo binario `.skill` manualmente desde la carpeta `skills/`, puedes instalarlo localmente:

```bash
gemini skills install ./ruta/al/archivo/nombre-de-la-skill.skill
```

## 🏗️ Cómo contribuir
Si quieres añadir una nueva skill a este monorepo:
1. Crea una nueva carpeta con el nombre de tu skill.
2. Asegúrate de incluir un archivo `SKILL.md` con la definición de la habilidad.
3. Sigue la estructura de carpetas: `assets/`, `references/` y `scripts/`.

---
Creado por [pfelipm](https://github.com/pfelipm)
