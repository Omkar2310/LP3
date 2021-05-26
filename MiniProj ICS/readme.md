## FOR SQL INJECTION
Steps to run
1. pip install flask
2. pip install flask-cors
3. Run python api.py file
4. Open index.html file on browser
5. Enter a' OR 1=1 OR 'b in image input box
6. Submit click and you see Connection Established.


## FOR CROSS SITE SCRIPTING

Steps to run

1. Open index.html on browser
2. Now write any  Test Message in message field and in Image field write invalid-page.com/no-image!jpg" onerror="alert('Hacked!')".
3. CLick submit you are alerted HACKED!!!.
