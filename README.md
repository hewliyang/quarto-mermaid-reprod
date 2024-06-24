# reprod

### Steps

requirements: a TeX distribution & headless Chrome

Then

```
quarto render --to=pdf
```

### Expected

`nested/mermaid_files/` is cleaned up

### Actual

`nested/mermaid_files/` is not cleaned up after successful render, but `mermaid_files/` at the root of the project was.
