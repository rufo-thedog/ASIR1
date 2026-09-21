# Documentación UD1 - Lenguaje de Marcas

## Introducción a los lenguajes de marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.

### Clasificación de los lenguajes de marcas

| Tipo                       | Uso                           | Ejemplos           |
| -------------------------- | ----------------------------- | ------------------ |
| Presentación               | Formatear documentos de texto | HTML, CSS          |
| Intercambio de información | Almacenar información         | XML, RSS           |
| Documentación              | Documentar proyectos          | Markdown, Wikitext |

## Instalación y configuración del entorno

1. Instalación de [VS Code](https://code.visualstudio.com/download?_exp_download=d53503e735)

2. Instalación de addons

- [Live Preview](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [Markdown All-in-One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [HTML / CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

3. Instalación de Git

```bash
sudo apt install git
```

4. Configuración del repositorio

```bash
git remote add origin https://github.com/rufo-thedog/linguaxemarcas
git branch -M main
git push -u origin main
```

5. Conectar

```bash
git add .
git commit -m "Comentario descriptivo"
git push
```

## Descripción de los plugins

| Nombre              | Uso                                                    | Imagen |
| ------------------- | ------------------------------------------------------ | ------ |
| XML                 | Facilita la escritura y autocompletado de XML         |        |
| Live Preview        | Permite previsualizar documentos                       |        |
| HTML / CSS Support  | Facilita la escritura y autocompletado de HTML y CSS |        |
| Markdown All-in-One | Facilita la escritura de documentos Markdown          |        |