# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a LaTeX-based master's thesis document for the Universidad Técnica Particular de Loja (UTPL). The thesis focuses on developing a mobile prototype for automatic water meter reading using image processing techniques, targeted at rural water management organizations (JAAPS) in Ecuador.

**Language**: Spanish  
**Institution**: Universidad Técnica Particular de Loja (UTPL)  
**Program**: Maestría en Inteligencia Artificial Aplicada  
**Topic**: Computer Vision and OCR for water meter reading in rural communities

## Build and Compilation Commands

### Primary Build Process (Required)
The document MUST be compiled with XeLaTeX (not pdfLaTeX) due to Arial font requirements:

```bash
# Complete compilation process (recommended)
xelatex main.tex    # First pass
biber main          # Process bibliography
xelatex main.tex    # Second pass (references)
xelatex main.tex    # Third pass (finalize indices)
```

### Quick Build (text-only changes)
```bash
xelatex main.tex
```

### Output Location
The compiled PDF is generated at: `build/main.pdf`

## Document Architecture

### Core Structure
- **main.tex**: Master document with all LaTeX configuration and includes
- **chapters/**: Main content chapters (chapter1.tex, chapter2.tex, etc.)
- **sections/**: Preliminary sections (cover, abstract, introduction, etc.)
- **references.bib**: Specialized bibliography (50+ references on OCR, computer vision, rural water management)
- **figures/**: Image assets including institutional logos

### Chapter Organization
- **Chapter 1**: Introduction (COMPLETED) - contextualizes rural water management problems
- **Chapter 2**: Theoretical Framework (STRUCTURE DEFINED) - covers JAAPS, computer vision, OCR theory
- **Chapters 3-5**: Methodology, Results, Discussion (PENDING)

### Critical LaTeX Configuration
- **Font**: Arial 11pt system font (requires XeLaTeX)
- **Margins**: 2.54cm all sides
- **Line spacing**: Double spacing throughout
- **Indentation**: 1.27cm first-line indent from "Introducción" onward
- **Page numbering**: Roman numerals (preliminaries) → Arabic (content starting from "Resumen")
- **Bibliography**: APA 7 style using biblatex with biber backend

## UTPL Format Requirements

The document strictly follows UTPL institutional formatting standards detailed in `FORMAT.md`:

### Heading Hierarchy
1. **Chapter titles**: Centered, bold, 11pt, with "Capítulo [word number]" format
2. **Sections**: Left-aligned, bold, 11pt, numbered
3. **Subsections**: Left-aligned, bold italic, 11pt, numbered
4. **Level 4**: Indented, bold, inline with period
5. **Level 5**: Indented, bold italic, inline with period

### Page Structure
- Preliminaries: Roman numerals (i, ii, iii...)
- Content: Arabic numerals starting from 1 at "Resumen"
- All pages numbered top-right corner

### Tables and Figures
- Arial 10pt for captions and content
- Bold "Tabla/Figura N" followed by italic title
- Centered on page with left-aligned notes

## Working with Bibliography

The bibliography uses specialized academic sources focused on:
- OCR and Deep Learning techniques
- Computer Vision for industrial applications
- Rural water management in Latin America
- Mobile development frameworks
- TensorFlow Lite and edge computing

### Adding References
```latex
% In text citation
\parencite{AuthorYear}

% Add to references.bib in APA format
@article{AuthorYear,
  author = {First Author and Second Author},
  title = {Article Title},
  journal = {Journal Name},
  year = {2024},
  doi = {10.xxxx/xxxx}
}
```

## Development Status

### Completed ✅
- Complete LaTeX setup and configuration
- Chapter 1 (Introduction) fully developed
- Bibliography compilation with 50+ specialized references
- UTPL format implementation
- Chapter 2 structure planning

### In Progress 🔄
- Chapter 2 content development (theoretical framework)
- Specialized content on computer vision and OCR

### Important Notes
- NEVER use pdfLaTeX - document will fail due to Arial font dependency
- Always maintain double spacing and exact margin specifications
- Preserve UTPL-specific formatting for institutional compliance
- The project addresses real social problems in rural Ecuador using AI techniques

## Content Guidelines

When working with content:
- Maintain academic Spanish writing style
- Focus on technical precision for computer vision and OCR topics
- Ensure alignment with rural development and sustainability themes
- Reference specialized literature appropriately using APA 7 format