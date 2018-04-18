This tutorial is made using Zxing library.
Setup steps:
1. Add dependency
2. Add camera permission
3. Edit Xml
4. Write java code, to start scanner

	zXingScannerView =new ZXingScannerView(getApplicationContext());
    setContentView(zXingScannerView);
    zXingScannerView.setResultHandler(this);
    zXingScannerView.startCamera();
	
5. Get Result. Done
