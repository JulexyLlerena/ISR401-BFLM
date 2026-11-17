# ISR401-BFLM
Repositorio para organizar tareas grupales

## Cómo compilar FORM-PC-01

Informe grupal de ISR-401 (comparación de modelos de proceso de requisitos).

- Carpeta: `FORM_PC_01/`
- Archivo principal: `FORM_PC_01/main.tex`
- Compilador: pdfLaTeX (en Overleaf, menú Compiler → pdfLaTeX)
- Paquetes usados: babel (spanish), geometry, array, tabularx, booktabs,
  enumitem, float, longtable, hyperref, placeins
- No usa bibliografía externa ni figuras.

**En Overleaf:** abrir el proyecto, seleccionar `main.tex` y pulsar Recompile.

**En local:**

    cd FORM_PC_01
    pdflatex main.tex
    pdflatex main.tex

Se compila dos veces para que las tablas largas y la numeración queden
correctas. El resultado es `main.pdf`.

## Cómo compilar GA-TL-02 - FORM

Taller de entrevista estructurada y design thinking aplicados al PFC (ISR-401).

- Carpeta: `GA/TL-02/`
- Archivo principal: `GA/TL-02/main.tex`
- Compilador: pdfLaTeX (en Overleaf, menú Compiler → pdfLaTeX)
- Paquetes usados: babel (spanish), geometry, array, tabularx, booktabs,
  longtable, enumitem, float, placeins, xcolor, hyperref
- No usa bibliografía externa ni figuras.

**En Overleaf:** abrir el proyecto, seleccionar `main.tex` y pulsar Recompile.

**En local:**

    cd GA/TL-02
    pdflatex main.tex
    pdflatex main.tex

Se compila dos veces para que las tablas largas queden correctas.
El resultado es `main.pdf`.

**Evidencias:** el audio del ensayo y el consentimiento firmado no están en
este repositorio. Se guardan en una carpeta institucional privada compartida
con el docente; el manifiesto con nombre, fecha, duración y huella SHA-256
está en la sección «Consentimiento informado y registro de evidencias» del
documento.
