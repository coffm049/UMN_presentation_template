# Create new presentation from template
Be in templates folder
```
mkdir samplepres && \
  cd samplepres && \
  quarto use template --no-prompt ../quarto-organization-template && 
  quarto render samplepres.qmd && \
  open *html
```



Template taken from
https://github.com/mcanouil/quarto-revealjs-storybook
