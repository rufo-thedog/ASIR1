# Documentación UD1 Lenguaje de Marcas

## Introducción a Lenguaje de marcas

### Definición
Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.


### Clasificación de Lenguaje de Marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Formatear documentos de texto|HTMl, CSS|
|Intercambio de información|Almacenar información|XML, RSS|
|Documentación|Documentar proyectos|Markdown, Wikitext|

## Instalación y configuración del entorno

1. Instalación [VSCode](https://code.visualstudio.com/download?_exp_download=d53503e735)

2. Instalación addons
  - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  - [Markdown All-in-One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - [HTML / CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

3. Instalación Git
   ```bash 
   sudo apt install git
   ```

5. Configurar repositorio en la carpeta principal del proyecto
  ```bash 
    git remote add origin https://github.com/rufo-thedog/linguaxemarcas
    git branch -M main
    git push -u origin main
  ```
6. Conectar 
    ```bash 
   git add . 
   git commit -m "Comentario descriptivo"
   git push
   ```

## Descripción de plugins

|Nombre|Uso|Imagen|
|------|------|---|
XML| Facilita sintaxis y autocompleta XML| ![No se](/UD1/img/logoa1.png)
Live Preview|Permite previsualizar |![jeje](/UD1/img/logoa2.png)
|HTML / Support| Facilita sintaxis y autocompleta XML| ![jejeje](/UD1/img/logoa3.png)
MarkDown AIO|Escribe MKDWN|![jejeje](/UD1/img/logoa4.png)
