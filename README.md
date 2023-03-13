# Integrate_ChatGPT_in_Whatsapp
You have to run both the files main.go and server.py in different terminals .
You'll need to run WhatsApp from a phone number using the golang library I'm using.
You'll run a dedicated browser in another window that's controlling ChatGPT.

To run you have to fllows these steps

1. Download the zip file or clone using git clone https://github.com/amanray33541/What-s-app-with-ChatGPT.git
2. Extract the zip file
3. Open the Terminal and go to directory
4. install the following thing
  a.Python :- https://www.python.org/downloads/
  b.Golang :- https://jmeubank.github.io/tdm-gcc/
5. install the following library using pip (or any)
6. pip install flask
pip install playwright
pip install virtualenv
pip install os-sys
pip install (if any other library still required
6.run the file on terminal on same directory as
  python server.py
  it will redirect to firefox if you want to open in chrome use chromium instead of firefox in server.py file at line 16
7.open new terminal on same directory and run
  go run main.go
  It will create a QR code
  open what's app in mobile and link device by scanning the qr 
8. message to that what's app and you will get chat gpt reply

