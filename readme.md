# ICONS FONT - ICOMOON
Pacote de icones vetoriais no formato de SVG ou fonte, documentação para configurações e atualizações disponíveis aqui: [Repositório de ícones do frontend](https://confluence.getnet.com.br:8444/pages/viewpage.action?pageId=226747540)

---
title: "Include external html file"
output: html_document
---

```{r generate-external-report, include=FALSE}
rmarkdown::render('embedded_file.Rmd')
```

External `HTML` file can be included in an `<iframe>` element:

```{r, echo=FALSE}
htmltools::tags$iframe(title = "My embedded document", src = "demo.html")
