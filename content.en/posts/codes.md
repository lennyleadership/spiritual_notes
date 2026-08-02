---
weight: 01
title: Codes
author: Lenny Lin
date: 2026-08-02
linktitle: 
---

# Codes to fix the brokeness of a paragraph
text <- "

"

clean <- gsub("[\r\n]+", " ", text)
clean <- gsub("\\s+", " ", clean)
clean <- trimws(clean)


cat(clean)

