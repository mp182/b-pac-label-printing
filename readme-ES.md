# Imprimiendo Etiquetas con b-PAC 🖨

Este es un ejemplo de cómo imprimir etiquetas con [Código QR](https://es.wikipedia.org/wiki/C%C3%B3digo_QR) con [b-PAC](https://www.brother.co.jp/eng/dev/bpac/index.aspx).

## Requerimientos

Antes de empezar, tenés que estar seguro de tener:

- Instalada la última versión de [b-PAC Client Component Only](https://www.brother.co.jp/eng/dev/bpac/download/index.aspx).\
**❗ Nota:** Elegí la versión que corresponda para tu Sistema Operativo (x86 - x64).

- Instalada la última versión de [P-touch Editor](https://support.brother.com/g/b/productsearch.aspx?c=us&lang=en&content=dl).

- Instalada la extensión de Chrome [Brother b-PAC Extension](https://chrome.google.com/webstore/detail/brother-b-pac-extension/ilpghlfadkjifilabejhhijpfphfcfhb). Esta extensión te permite controlar impresoras de etiquetas Brother desde Chrome usando b-PAC.

- Instalada la última versión del [Printer Driver](https://support.brother.com/g/b/productsearch.aspx?c=us&lang=en&content=dl).

## Uso

- Reemplazá la ruta MODEL_FILE por una de tu preferencia. Tené en cuenta que tenés que tener acceso de Admin a esa ruta.

```javascript
 const MODEL_FILE = "C:\\Users\\user\\Desktop\\label.lbx";
```

- Después de eso, podés copiar el archivo label.lbx de *assets/label/label.lbx* y copiarlo en la ruta del punto anterior.

## Algunas cosas a tener en cuenta 👈

Más allá del código, hay algunos puntos a tener en cuenta respecto a la impresora.

- Asegurate que la luz "Editor Lite" está apagada. Para eso mantené apretado el botón por unos segundos.

- Tenés que chequear el tamaño del papel tanto en el editor P-Touch como en las propiedades de la impresora. Tienen que coincidir.

## Documentos Útiles 📃

Para desarrollar este ejemplo leí y copié algo de código de:

- http://download.brother.com/pub/com/dev/pdf/bpac_webapplication_eng.pdf

- https://stackoverflow.com/questions/59363053/adding-a-script-as-module-in-wordpress-admin-area

## Contacto 📧

Si querés contactarme podés hacerlo a  <mpablo182@gmail.com>.
