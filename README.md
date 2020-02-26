# simple-https-server
Simple Python Based HTTPS Server for localhost testing with Sauce Connect

A self-signed SSL cert is included, but if you need to generate a new SSL certificate, use the following command:

```openssl req -new -x509 -keyout server.pem -out server.pem -days 365 -nodes```

Run the server as follows:

```python simple-https-server.py```

Then in your browser (or in a test on Sauce using Sauce Connect), visit:

https://localhost:8000
    

## Test pages currently included:

* Query String Parser: https://localhost:8000/parseQueryString.html
  
  To test parsing of a query string, add one to the URL!  
  e.g. https://localhost:8000/parseQueryString.html?test=yes&foo=bar
