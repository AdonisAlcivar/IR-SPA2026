# TA-IND-01: IEEE 29148 y tipos de requisitos de un sistema conocido

**Autor:** Anderson Adonis Alcívar Vélez
**Paralelo:** A
**Sistema analizado:** Aplicación móvil de Netflix

Trabajo individual que aplica la norma ISO/IEC/IEEE 29148:2018 a un sistema
que uso con frecuencia, clasificando sus requisitos con ISO/IEC 25010:2023.

## Contenido

| Archivo / carpeta | Descripción |
|---|---|
| `main.tex` | Código fuente del informe en LaTeX |
| `main.pdf` | Informe compilado |
| `capturas/` | 3 capturas propias de la aplicación |
| `.gitignore` | Excluye los archivos auxiliares de LaTeX |

## Secciones del informe

1. Resumen analítico de la norma ISO/IEC/IEEE 29148:2018
2. Glosario de 10 términos de la cláusula 3
3. 15 requisitos (primera versión)
4. Tabla de clasificación y criterios de aceptación
5. Autoevaluación y versión corregida
6. Reflexión
7. Anexo A: capturas propias

## Cómo compilar

Desde la carpeta `TA-IND-01/`, ejecutar dos veces:

```bash
pdflatex main.tex
pdflatex main.tex
```

Requiere una distribución de LaTeX completa (TeX Live o MiKTeX) con los
paquetes `lmodern`, `microtype`, `longtable`, `booktabs`, `enumitem`,
`graphicx`, `fancyhdr` y `hyperref`. Las imágenes se cargan con rutas
relativas desde `capturas/`.

## Nota

Los requisitos salen de lo que observo como usuario de la aplicación, no de
documentación interna de la empresa. Los umbrales son supuestos razonables y
no valores oficiales.