# Printing labels with b-PAC 🖨

This is an example of how to print a label with a [QR Code](https://en.wikipedia.org/wiki/QR_code) with [b-PAC](https://www.brother.co.jp/eng/dev/bpac/index.aspx).

## Requeriments

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of [b-PAC Client Component Only](https://www.brother.co.jp/eng/dev/bpac/download/index.aspx).\
**❗ Note:** Choose the version that corresponds to your Operating System (x86 - x64).

- You have installed the latest version of [P-touch Editor](https://support.brother.com/g/b/productsearch.aspx?c=us&lang=en&content=dl).

- You need to install [Brother b-PAC Extension](https://chrome.google.com/webstore/detail/brother-b-pac-extension/ilpghlfadkjifilabejhhijpfphfcfhb). This extension allows you to control Brother label and mobile printers from Chrome using b-PAC.

- You have installed the latest version of the [Printer Driver](https://support.brother.com/g/b/productsearch.aspx?c=us&lang=en&content=dl).

## Using

- Replace the path MODEL_FILE with one of your preference. Keep in mind you need Admin access to that path.

` const MODEL_FILE = "C:\\Users\\user\\Desktop\\label.lbx";
`

- After that, you can take label.lbx file from *assets/label/label.lbx* and copy to the previous path.

## Related Docs

To develop this example I read and copy-pasted some code from:

- http://download.brother.com/pub/com/dev/pdf/bpac_webapplication_eng.pdf

- https://stackoverflow.com/questions/59363053/adding-a-script-as-module-in-wordpress-admin-area

## Contact 📧

If you want to contact me you can reach me at <mpablo182@gmail.com>.