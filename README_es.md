<h1 align="center">Obsidian VSCode Editor</h1>

<p align="center">
    <img alt="Release version" src="https://img.shields.io/github/v/release/lz-migra/obsidian-vscode-editor?style=for-the-badge">
    <img alt="Download count" src="https://img.shields.io/github/downloads/lz-migra/obsidian-vscode-editor/total?style=for-the-badge">
    <img alt="License" src="https://img.shields.io/github/license/lz-migra/obsidian-vscode-editor?style=for-the-badge">
</p>

<p align="center">
    <span>Un plugin de Obsidian para visualizar y editar archivos de código con la experiencia de VSCode, mantenido activamente y con nuevas mejoras.</span>
    <br/>
    <a href="/README.md">English</a>
    ·
    <a href="/README_es.md">Español</a>
</p>

---

## 🚀 Estado del proyecto

Este es un fork mantenido del proyecto original [`sunxvming/obsidian-vscode-editor`](https://github.com/sunxvming/obsidian-vscode-editor), el cual no recibe actualizaciones desde hace más de 3 años.  
Aquí encontrarás una versión **activa y mejorada**, con correcciones y nuevas funciones:

- 📝 **Menú contextual renovado** — reescrito por completo, ahora independiente de Monaco Editor y mejor integrado con Obsidian.  
- 🌍 **Soporte en español** — localización completa para usuarios hispanohablantes.  
- 📋 **Correcciones de pegado** — comportamiento consistente tanto con `Ctrl+V` como con el menú contextual.  
- ⚡ **Compatibilidad** — mejor soporte con versiones recientes de Obsidian y más estabilidad en el editor.  

---

## 📖 Acerca del plugin

Obsidian por defecto no soporta la edición de muchos tipos de archivos de código.  
Este plugin soluciona el problema integrando el núcleo del editor de VSCode (basado en [Monaco Editor](https://microsoft.github.io/monaco-editor/)) directamente en Obsidian.  

Permite ver y editar múltiples lenguajes de programación:  
`C`, `C++`, `C#`, `CSS`, `Go`, `HTML`, `Java`, `JavaScript`, `JSON`, `Python`, `Ruby`, `Rust`, `Shell`, `XML`, `YAML`, `INI`, entre otros.  

Ya no necesitas abrir un editor externo: todo se hace sin salir de Obsidian.  

---

## ✨ Características principales

- Funciona **sin depender de servicios externos**: utilizable incluso sin conexión a internet.  
- Edición completa de archivos en múltiples lenguajes, como en VSCode.  
- Personalización de colores, temas claro/oscuro y tamaño de fuente (`Ctrl + rueda del mouse`).  
- Edición de bloques de código dentro de documentos Markdown.  
- Vista previa rápida de enlaces internos a archivos de código.  
- Ajuste automático de líneas (`Alt+Z`).  
- Opción de mostrar/ocultar números de línea, guías de indentación y minimapa.  
- Atajos de teclado familiares para usuarios de VSCode.  
- Botones y comandos para crear archivos de código nuevos.  

---

## ⌨️ Atajos soportados

La mayoría son consistentes con VSCode. Ejemplos:

| Categoría    | Atajo                  | Acción                    |
|--------------|------------------------|---------------------------|
| Ctrl         | `ctrl + c`             | Copiar                    |
|              | `ctrl + x`             | Cortar                    |
|              | `ctrl + v`             | Pegar                     |
|              | `ctrl + s`             | Guardar                   |
|              | `ctrl + f`             | Buscar                    |
|              | `ctrl + h`             | Reemplazar                |
|              | `ctrl + z`             | Deshacer                  |
|              | `ctrl + y`             | Rehacer                   |
|              | `ctrl + /`             | Comentar línea            |
|              | `ctrl + d`             | Duplicar línea            |
|              | `ctrl + [`             | Disminuir indentación     |
|              | `ctrl + ]`             | Aumentar indentación      |
|              | `ctrl + ↑`             | Mover línea arriba        |
|              | `ctrl + ↓`             | Mover línea abajo         |
| Ctrl+Shift   | `ctrl + shift + k`     | Eliminar línea actual     |
|              | `ctrl + shift + [`     | Colapsar bloque de código |
|              | `ctrl + shift + ]`     | Expandir bloque de código |
| Alt          | `alt + z`              | Ajuste automático de línea|

---

## 🔧 Instalación

### Desde la comunidad de plugins de Obsidian  
🚫 **Aún no disponible en la tienda oficial de plugins.**

### Instalación manual  
1. Descarga la última versión desde la sección de [Releases](https://github.com/lz-migra/obsidian-vscode-editor/releases/latest).  
2. Descomprime el archivo y copia la carpeta en:
`<tu-vault>/.obsidian/plugins/`
3. Abre Obsidian y ve a **Ajustes > Complementos de la comunidad**.  
4. Activa la opción **Habilitar complementos de la comunidad**.  
5. Busca en la lista inferior **Obsidian VSCode Editor** y actívalo con el interruptor.  

---

## 📬 Contacto

Cualquier sugerencia, bug o pregunta, puedes abrir un issue aquí:  
👉 [GitHub Issues](https://github.com/lz-migra/obsidian-vscode-editor/issues)
