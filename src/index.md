---
lang: ru

title: "Document Name"
author:
  - Surname Name Patronymic

institute: "University Name"
date: yyyy-mm-dd
abstract: |
  Abstract content...
  **Keywords:** Pandoc, Markdown, documents.
keywords: [Pandoc, Markdown, documents]
geometry: "left=3cm,right=1.5cm,top=2cm,bottom=2cm"
fontsize: 14pt
mainfont: "Times New Roman"

bibliography: references.bib
csl: ../config/citation-style.csl
---

# Annotation

!include src/abstract.md

# Chapter Name

!include src/chapters/01-chapter-name.md
