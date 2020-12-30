# QR-Code-generator-using-python
Creating QR Code using Pyton

import pyqrcode   //importing a python module

def qrcode():       // defining a function
    qr=pyqrcode.create(input())       //input the characters or words of qr code to be generated
    qr.png("QRcode.png", scale=6)       //generating qr code with a scale of 
    print("QR Generated")               // printing a string -QR Generated   



if _name__ == "__main__":           //calling the function
    qrcode()
