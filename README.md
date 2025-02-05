# QR-Bill

With the introduction of ISO 20022 in 2020, the new QR-bill will replace all inpayment slips. This is a LaTeX invoice template that include the new Swiss QR Code.

The QR-bill is also known as :

	- QR-Facture (FR)
	- QR-Rechnung (DE)
	- Fattura QR (IT)

### How to use
You just have to edit the ```paymentdata.txt``` file and compile the ```invoice.tex``` using this command :
```sh
$ make
```

Was using https://github.com/claudep/swiss-qr-bill to generate the qr bill part as svg before, but generating the whole document took too long.

### Version
0.2 => reworked the Format according to V2 Style Guide https://www.paymentstandards.ch/dam/downloads/style-guide-de.pdf

### More informations

Vidéo de présentation (PostFinance) :
https://www.youtube.com/watch?v=qQI0bPNYrmw

Swiss Implementation Guidelines QR-bill :
https://www.paymentstandards.ch/dam/downloads/ig-qr-bill-en.pdf

Media Release :
https://www.paymentstandards.ch/dam/downloads/media-release-qr-bill-en.pdf

More infos :
https://www.paymentstandards.ch/fr/home/softwarepartner/qr-bill.html
