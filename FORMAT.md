# UTPL Thesis Formatting Guide (Quick Reference)

> Summarised from *Consideraciones generales para aplicar en el Trabajo de Titulación* — Biblioteca UTPL. Use this as a checklist for automated format validation.

---

## 1 · General Page Setup

| Item                 | Requirement                                                                         |
| -------------------- | ----------------------------------------------------------------------------------- |
| **Paper size**       | A4 (21 × 29.7 cm)                                                                   |
| **Margins**          | 2.54 cm (all sides)                                                                 |
| **Body font**        | Arial 11 pt                                                                         |
| **Tables & figures** | Arial 10 pt                                                                         |
| **Line spacing**     | Double everywhere; table/figure *content* = 1.5 lines                               |
| **Paragraph indent** |  1.27 cm first‑line *from* **Introducción** onward; prelim pages have **no** indent |
| **Extra space**      | Never add space before/after paragraphs or headings                                 |

---

## 2 · Page Numbering

| Section                 | Numeral style                 | Starts at    | Position  |
| ----------------------- | ----------------------------- | ------------ | --------- |
| Carátula                | *counted* but **not printed** | —            | —         |
| Preliminaries ≤ Índice  | Lower‑case Roman (i, ii, …)   | Carátula = i | Top‑right |
| From **Resumen** onward | Arabic (1, 2, …)              | Resumen = 1  | Top‑right |

---

## 3 · Heading Hierarchy & Typography

| Level | Example                 | Style                             | Alignment | Terminates            |
| ----- | ----------------------- | --------------------------------- | --------- | --------------------- |
| 1     | *Capítulo Uno*          | **Bold**, 14‑18 pt, UPPERCASE     | Centred   | *(no period)*         |
| 2     | *Marco teórico*         | **Bold**, 11 pt                   | Left      | *(no period)*         |
| 3     | *Aprendizaje profundo*  | **Bold Italic**, 11 pt            | Left      | *(no period)*         |
| 4     | *Métodos supervisados.* | **Bold**, indented 1.27 cm        | Inline    | `.` then text follows |
| 5     | *Algoritmo SVM.*        | **Bold Italic**, indented 1.27 cm | Inline    | `.` then text follows |

**Rules**

* Never prefix headings with numbers, letters, or bullets.
* Never insert blank lines before/after a heading (even at page breaks).

```markdown
# Capítulo Uno
## Marco teórico
### Aprendizaje profundo
    #### Métodos supervisados. El aprendizaje...
        ##### Algoritmo SVM. Su aplicación...
```

---

## 4 · Carátula (Cover Page)

* Main headings (University, Faculty, Degree): **Arial 18 pt, bold, UPPERCASE, centred**.
* Motto lines: Bell MT 16 pt, *italic*, centred.
* Thesis title: **Arial 16 pt, bold, sentence case, centred** (omit final period).
* Author & Director block: Arial 12 pt, left‑aligned, double‑spaced.
* City & Year: Arial 12 pt, UPPERCASE, centred.

---

## 5 · Tables & Figures

1. Centre the object on the page.
2. Caption *above* the object:

   * **Table/Figure N** (bold)
   * *Title in italics*
3. Use Arial 10 pt for captions and content.
4. **Nota.** (italic word) left‑aligned below the object, double‑spaced.
5. Cite sources or copyright when not self‑created.

> *Example*
> **Tabla 1** *Distribución de acceso a Internet*
> *(table here)*
> *Nota.* Adaptado de Rojas (2019).

---

## 6 · Sections Order

1. Carátula
2. Aprobación del Director
3. Declaración de Autoría
4. Dedicatoria
5. Agradecimiento
6. Índice (contenido, tablas, figuras)
7. **Resumen** (≤ 180 words) + *Palabras clave* (max 3)
8. **Abstract** + *Keywords*
9. **Introducción** (≤ 2 pages)
10. Capítulos 1‑n (Marco teórico, Metodología, Resultados)
11. **Conclusiones** (new page)
12. **Recomendaciones** (new page)
13. **Referencias**
14. **Apéndices** (A, B, C…)

---

## 7 · Section‑Specific Notes

### 7.1 Resumen / Abstract

* Single paragraph, ≤ 180 words.
* Double‑spaced, Arial 11 pt, justified, **no indent**.
* *Palabras clave:* / *Keywords:* in *italics* followed by 2‑3 terms separated by commas.

### 7.2 Introducción

* Arial 11 pt, double‑spaced, justified, **first‑line indent 1.27 cm**.
* Summarise problem, objectives, methodology, chapter outline, and significance in ≤ 2 pages.

### 7.3 Conclusiones & Recomendaciones

* Each starts on a **new page**.
* Paragraphs indented; **do not** number or use bullets.

### 7.4 Referencias

* APA 7 format, alphabetical order.
* Hanging indent 1.27 cm.
* Double‑spaced, Arial 11 pt.
* Shorten URLs with Bitly.

### 7.5 Apéndices

* Label A, B, C… in heading and in every table/figure (e.g., **Tabla A1**).
* Tables/Figures inside appendices are **not** listed in the main indices.

---

## 8 · Submission Checklist

* [ ] Word document uses template & editing is enabled.
* [ ] All margins, fonts, spacing, and heading styles comply.
* [ ] Page numbers: prelim = Roman, body = Arabic; carátula counted but not printed.
* [ ] All tables/figures captioned, noted, and cited.
* [ ] References use APA 7 + hanging indent; links shortened.
* [ ] PDF verified after library corrections; re‑sent to **[bbc\_revision@utpl.onmicrosoft.com](mailto:bbc_revision@utpl.onmicrosoft.com)**.

---

*(Generated for LLM ingestion — last updated 2025‑06‑12)*
