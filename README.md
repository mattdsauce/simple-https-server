# simple-https-server
Simple Python Based HTTPS Server for localhost testing with Sauce Connect

If you need to generate a new SSL certificate, use the following command:
    openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes

Run the server as follows:
    python simple-https-server.py

Then in your browser, visit:
    https://localhost:8000
    
    
