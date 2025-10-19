# Guía de Organización de Documentos

## 📋 Tipos de Documentos Soportados

### Textos
- `.txt` - Archivos de texto plano
- `.rtf` - Rich Text Format
- `.doc`, `.docx` - Documentos de Word

### Markdown
- `.md` - Archivos Markdown
- `.mdx` - Markdown extendido

### PDFs
- `.pdf` - Documentos PDF

### Imágenes
- `.jpg`, `.jpeg` - Imágenes JPEG
- `.png` - Imágenes PNG
- `.gif` - Imágenes GIF
- `.svg` - Gráficos vectoriales
- `.webp` - Imágenes WebP

### Hojas de Cálculo
- `.xls`, `.xlsx` - Excel
- `.csv` - Valores separados por comas
- `.ods` - OpenDocument Spreadsheet

### Presentaciones
- `.ppt`, `.pptx` - PowerPoint
- `.odp` - OpenDocument Presentation

### Otros
- Cualquier otro tipo de documento que no encaje en las categorías anteriores

## 💡 Mejores Prácticas

1. **Nombres de Archivo**: Usa nombres descriptivos y claros
   - ✅ `informe-ventas-2024.pdf`
   - ❌ `documento1.pdf`

2. **Organización**: Crea subcarpetas si tienes muchos documentos del mismo tipo
   ```
   documentos/textos/
   ├── informes/
   ├── notas/
   └── borradores/
   ```

3. **Codificación**: Para archivos de texto, usa UTF-8 cuando sea posible

4. **Versionado**: Si guardas múltiples versiones, incluye la fecha o versión en el nombre
   - `proyecto-v1.0.md`
   - `proyecto-2024-10-19.md`

## 🔍 Uso con IA

Este repositorio puede ser utilizado con herramientas de IA como:
- **GitHub Copilot**: Para sugerencias de código y texto
- **ChatGPT**: Como referencia de documentos
- **Modelos de procesamiento de lenguaje**: Para análisis de texto
- **Herramientas de OCR**: Para extraer texto de imágenes

## 📌 Notas

- Los archivos `.gitkeep` en cada carpeta aseguran que las carpetas vacías se mantengan en el repositorio
- Puedes eliminar estos archivos una vez que añadas contenido a las carpetas
- Si necesitas una nueva categoría, simplemente crea una nueva carpeta en `documentos/`
