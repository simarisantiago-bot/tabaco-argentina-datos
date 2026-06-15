# Tabaco Argentina — Datos y simulador

Sitio web estático con datos sobre consumo de tabaco en Argentina y un simulador interactivo asociado al proyecto de ley **"Generación Libre de Humo"**.

## Contenido

- Datos epidemiológicos y de mortalidad atribuible al tabaquismo en Argentina.
- Visualizaciones del consumo por grupo etario, jurisdicción y producto.
- Simulador del impacto esperado del proyecto de ley "Generación Libre de Humo".
- Referencias a la normativa vigente y al proyecto en discusión.

## Estructura

Proyecto estático de un solo archivo, sin build:

- [`index.html`](index.html) — sitio completo (HTML, CSS y JS embebidos).

## Desarrollo local

Para previsualizar el sitio sin dependencias:

```powershell
python -m http.server 8080
# Abrir http://localhost:8080/
```

## Despliegue

Hosteado en Vercel como sitio estático. Cada push a `main` redespliega automáticamente.

## Licencia

Material de divulgación con fines informativos sobre política pública.
