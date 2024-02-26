# CSS3

## Variables en css

```css
:root {
    --color-principal: red;
    --fuente: Arial, Verdana;
    --fuente-size: 35px;
}

h1 {
    color: var(--color-principal);
    font-family: var(--fuente)
}
```