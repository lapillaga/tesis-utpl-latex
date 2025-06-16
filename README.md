# Tesis de Maestría - Prototipo Móvil para Lectura Automática de Medidores de Agua

## 📋 Información General

**Título**: Prototipo móvil para la lectura automática de medidores de agua potable mediante técnicas de procesamiento de imágenes dirigido a las Juntas Administradoras de Agua Potable y Saneamiento (JAAPS) en el sector rural del Ecuador.

**Programa**: Maestría en Inteligencia Artificial Aplicada  
**Institución**: Universidad Técnica Particular de Loja (UTPL)  
**Área de Investigación**: Visión por Computadora y Reconocimiento Óptico de Caracteres (OCR)  
**Contexto**: Gestión comunitaria del agua en zonas rurales del Ecuador

## 🎯 Objetivos del Proyecto

### Objetivo General
Desarrollar un prototipo móvil que permita la lectura automática de medidores de agua potable mediante técnicas de procesamiento de imágenes, orientado a optimizar la gestión de las JAAPS en el sector rural ecuatoriano.

### Objetivos Específicos
1. **Revisión Sistemática**: Análisis exhaustivo de literatura sobre OCR móvil aplicado a lectura de medidores
2. **Dataset Especializado**: Construcción de base de datos de imágenes de medidores en condiciones rurales
3. **Modelo de Deep Learning**: Desarrollo de algoritmo optimizado para dispositivos móviles
4. **Aplicación Android**: Implementación de app con procesamiento local (offline-first)
5. **Validación de Campo**: Pruebas en JAAPS representativas del sector rural

## 🏗️ Estructura del Proyecto

```
tesis/
├── main.tex                  # Documento principal de LaTeX
├── FORMAT.md                 # Guía de formato UTPL
├── references.bib            # Bibliografía especializada (50+ referencias)
├── .gitignore               # Configuración Git (permite main.pdf en build/)
├── chapters/                # Capítulos principales
│   ├── chapter1.tex         # ✅ Introducción (COMPLETADO)
│   └── chapter2.tex         # 🔄 Marco Teórico (estructura definida)
├── sections/                # Secciones preliminares
│   ├── cover.tex            # Carátula institucional
│   ├── abstract.tex         # Resumen en inglés
│   ├── summary.tex          # Resumen en español
│   ├── introduction.tex     # Introducción general
│   ├── approval.tex         # Aprobación del director
│   ├── authorship.tex       # Declaración de autoría
│   ├── dedication.tex       # Dedicatoria
│   ├── thanks.tex           # Agradecimientos
│   ├── conclusions.tex      # Conclusiones
│   └── recommendations.tex  # Recomendaciones
├── figures/                 # Recursos gráficos
│   ├── logo_utpl.jpg       # Logo institucional
│   └── example.jpg         # Imagen de ejemplo
├── build/                   # Archivos de compilación
│   └── main.pdf            # Documento final (tracked en Git)
└── appendices/             # Apéndices (futuro)
```

## 🔧 Requisitos Técnicos

### Herramientas de Compilación
- **XeLaTeX** (OBLIGATORIO - para fuente Arial)
- **BibTeX/Biber** (gestión de bibliografía)
- **LaTeX Distribution** (TeX Live, MiKTeX, etc.)

### Paquetes LaTeX Necesarios
```latex
fontspec        % Fuentes del sistema
babel           % Localización en español
biblatex        % Bibliografía moderna
hyperref        % Enlaces internos
geometry        % Configuración de página
setspace        % Interlineado
fancyhdr        % Encabezados y pies de página
```

### Configuración Específica
- **Fuente**: Arial 11pt (sistema)
- **Márgenes**: 2.54cm todos los lados
- **Interlineado**: Doble espacio
- **Numeración**: Romanos (preliminares) → Arábigos (contenido)
- **Bibliografía**: Estilo APA 7
- **Índices**: Automáticos (contenido, tablas, figuras)

## 🚀 Compilación

### Proceso Completo
```bash
# Navegar al directorio del proyecto
cd /path/to/tesis

# Compilación completa (recomendado)
xelatex main.tex    # Primera pasada
biber main          # Procesar bibliografía
xelatex main.tex    # Segunda pasada (referencias)
xelatex main.tex    # Tercera pasada (índices)
```

### Compilación Rápida (solo texto)
```bash
xelatex main.tex
```

### Verificar Salida
```bash
# El archivo final se genera en:
build/main.pdf
```

## 📚 Contenido Desarrollado

### ✅ Capítulo 1 - Introducción (COMPLETADO)
- **Contextualización**: Problemática del agua rural en Ecuador
- **Justificación**: Tecnológica, social y científica
- **Objetivos**: General y específicos claramente definidos
- **Alcance**: Limitaciones y delimitaciones del proyecto
- **Metodología**: Enfoque general de la investigación

### 🔄 Capítulo 2 - Marco Teórico (ESTRUCTURA DEFINIDA)
Secciones planificadas:
- **2.1** Gestión Comunitaria del Agua (JAAPS)
- **2.2** Fundamentos de Visión por Computadora
- **2.3** Reconocimiento Óptico de Caracteres (OCR)
- **2.4** Desarrollo de Sistemas Móviles Offline
- **2.5** Estado del Arte en Lectura Automática de Medidores

### ⏳ Capítulos Pendientes
- **Capítulo 3**: Metodología de Investigación
- **Capítulo 4**: Resultados y Análisis
- **Capítulo 5**: Discusión y Conclusiones

## 📖 Bibliografía Especializada

### Áreas de Investigación
- **OCR y Deep Learning**: 15+ referencias especializadas
- **Visión por Computadora**: Modelos optimizados para edge computing
- **Gestión Rural del Agua**: Contexto ecuatoriano y latinoamericano
- **Desarrollo Móvil**: Frameworks offline-first y TensorFlow Lite
- **Sostenibilidad**: ODS 6 y desarrollo rural

### Referencias Clave
- Técnicas de deep learning para lectura de medidores
- Implementaciones de TensorFlow Lite para dispositivos móviles
- Estudios sobre JAAPS en Ecuador y América Latina
- Frameworks de desarrollo Android modernas

## 🎯 Alcance y Limitaciones

### Alcance Técnico
- **Tipo de Medidores**: Solo analógicos (no digitales)
- **Plataforma**: Android únicamente
- **Procesamiento**: Local (sin dependencia de internet)
- **Validación**: JAAPS representativas del sector rural

### Limitaciones Reconocidas
- Prototipo funcional, no sistema comercial completo
- Condiciones de iluminación controladas
- Dataset limitado a medidores locales
- Validación en entorno controlado

## 💡 Contribuciones Esperadas

### Técnicas
- Modelo de OCR optimizado para dispositivos móviles
- Dataset especializado en medidores rurales ecuatorianos
- Aplicación Android con procesamiento offline

### Sociales
- Mejora en la gestión comunitaria del agua
- Reducción de errores en lectura manual
- Optimización de recursos en JAAPS rurales

### Científicas
- Aplicación práctica de IA en problemas sociales rurales
- Validación de técnicas de edge computing en contexto real
- Metodología replicable para otros países latinoamericanos

## 📊 Estado Actual

### Completado ✅
- Configuración LaTeX completa y funcional
- Capítulo 1 (Introducción) totalmente desarrollado
- Estructura del Marco Teórico definida
- Bibliografía especializada compilada
- Formato UTPL implementado correctamente

### En Desarrollo 🔄
- Contenido del Marco Teórico (Capítulo 2)
- Metodología de investigación
- Desarrollo del prototipo móvil

### Pendiente ⏳
- Capítulos 3-5 (Metodología, Resultados, Discusión)
- Resumen ejecutivo y Abstract
- Conclusiones y Recomendaciones finales
- Validación empírica del prototipo

## 🛠️ Desarrollo Futuro

### Próximos Pasos
1. **Completar Marco Teórico**: Desarrollo del contenido definido
2. **Implementar Prototipo**: Desarrollo de la aplicación Android
3. **Construir Dataset**: Recolección de imágenes de medidores
4. **Entrenar Modelo**: Implementación y optimización del algoritmo OCR
5. **Validar en Campo**: Pruebas en JAAPS reales

### Consideraciones Técnicas
- Mantener compatibilidad con XeLaTeX
- Documentar proceso de desarrollo del prototipo
- Preparar infraestructura para dataset de imágenes
- Planificar validación estadística de resultados

## 📞 Contacto y Soporte

### Configuración del Entorno
Si tienes problemas con la compilación:
1. Verificar instalación de XeLaTeX
2. Comprobar disponibilidad de fuente Arial
3. Instalar paquetes LaTeX faltantes
4. Revisar configuración de Biber/BibTeX

### Formato UTPL
Consultar `FORMAT.md` para detalles específicos del formato institucional requerido.

---

> **Nota**: Este proyecto representa una contribución significativa al campo de la inteligencia artificial aplicada a problemas sociales rurales, combinando tecnologías de vanguardia con necesidades reales de las comunidades ecuatorianas.

*Última actualización: Junio 2025*