# Qr/ Barcode Reader
This tutorial is made using Zxing library.
Setup steps:
- Add dependency
- Add camera permission
- Edit Xml
- Write java code, to start scanner
```sh
    zXingScannerView =new ZXingScannerView(getApplicationContext());
    setContentView(zXingScannerView);
    zXingScannerView.setResultHandler(this);
    zXingScannerView.startCamera();
```
	
- Get Result. Done
