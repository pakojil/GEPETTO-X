# GEPETTO-X
![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Language](https://img.shields.io/badge/language-Python-orange.svg) ![Status](https://img.shields.io/badge/status-beta-yellowgreen.svg)

**Generador Editorial para Publicaciones Estructuradas con Tipografía y Trazado Optimizado — XML-JATS**  

GEPETTO-X es un sistema avanzado de **generación editorial automática** que transforma documentos científicos estructurados en **XML-JATS** en publicaciones tipográficamente completas, listas para PDF paginado mediante **Vivliostyle**, con un enfoque de **Ciencia Abierta** y estándares de interoperabilidad.

El nombre hace referencia a *Gepetto*, el artesano de *Pinocho*, que transforma un bloque de madera inerte en un objeto vivo: de forma similar, **GEPETTO-X da “vida editorial” a los artículos XML-JATS**, preservando su estructura semántica y reproduciendo fielmente su layout.

---

## 🔹 Contexto y motivación

- Basado en estándares abiertos de publicación científica (**XML-JATS**).  
- Inspirado en iniciativas de **OpenPub** de la Universidad de Murcia (UMU) para gestión editorial y **Acceso Abierto**.  
- Permite convertir contenido académico semántico en PDFs de alta calidad **sin intervención manual**.  
- Compatible con workflows editoriales de revistas universitarias y repositorios de ciencia abierta.  

> *GEPETTO-X fortalece la interoperabilidad, la reutilización y la difusión abierta de la producción académica.*

---

## 🔹 Funcionalidades principales

1. **Inferencia semántica de layout**: interpreta la estructura de XML-JATS para decidir estilo, jerarquía de secciones y tipografía.  
2. **Clonación de layout**: reproduce el aspecto final de publicaciones existentes como referencia.  
3. **Composición tipográfica automatizada**: genera PDFs paginados y editables con **Vivliostyle**.  
4. **Integración con repositorios Open Access**: pensado para interoperar con OJS, Zenodo y otros sistemas académicos.  
5. **Pipeline modular y extensible**: compatible con futuras transformaciones XSLT, CSS paginado y adaptaciones de estilo institucional.

---

## 🔹 Requisitos

- Python >= 3.10  
- LXML  
- CSS paginado / Vivliostyle  
- Acceso a XML-JATS de artículos o revistas científicas  

---

## 🔹 Instalación

```bash
git clone https://github.com/tu-usuario/GEPETTO-X.git
cd GEPETTO-X
pip install -r requirements.txt
