---
title: Wiki 2DM
description: Base de conhecimento da 2DM
---

# 📚 Wiki 2DM

Bem-vindo à base de conhecimento da **2DM**.  
Aqui você encontra artigos, conceitos, projetos e pessoas organizados em formato de wiki.

---

## 🔎 Busca rápida

Use a **barra de busca** no canto da página para encontrar qualquer conteúdo instantaneamente.

---

## 🆕 Últimos 10 artigos publicados

```dataview
LIST
FROM "wiki-2dM/02_Artigos"
WHERE file.name != "02_Artigos"
SORT file.mtime DESC
LIMIT 10
