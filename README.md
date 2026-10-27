# Recibos El Molio

Programa para generar los recibos de mantenimiento de El Molio. Aquí solo se publican las versiones listas para usar.

## Instalar (Windows)

1. Descarga **[RecibosMolio_windows_amd64.exe](https://github.com/asloth/molio-recibos/releases/latest/download/RecibosMolio_windows_amd64.exe)**.
2. Crea una carpeta, por ejemplo `Documentos\Recibos`, y pon el archivo ahí. Puedes renombrarlo a `RecibosMolio.exe`.
3. Haz doble clic. Si Windows dice "Windows protegió su PC", entra a **Más información → Ejecutar de todas formas** (pasa porque el programa no está firmado).

La primera vez crea las carpetas `cuotas`, `output` y `contometer` al lado del programa.

## Usar

- Copia el Excel del mes en la carpeta **cuotas**.
- Abre el programa y elige **Generar recibos**. Muévete con las flechas, Enter para elegir, `/` para buscar un edificio, Esc para cancelar.
- Los PDF quedan en **output**.
- Para **Enviar recibos por correo** hace falta el archivo `.env` con la contraseña del correo en la misma carpeta (te lo pasan aparte, nunca lo compartas).

## Actualizar

Cuando hay una versión nueva, el programa lo avisa al abrir. Elige **Actualizar** en el menú, espera a que termine y vuelve a abrirlo. También funciona desde una terminal:

```
RecibosMolio.exe actualizar
```
