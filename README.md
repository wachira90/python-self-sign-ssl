# python-self-sign-ssl
python-self-sign-ssl

## Same thing but in different formatting

openssl \

  req \
  
  -newkey rsa:2048 -nodes \
  
  -keyout privkey.pem \
  
  -x509 -days 36500 -out certificate.pem \
  
  -subj "/C=US/ST=NRW/L=Earth/O=CompanyName/OU=IT/CN=www.example.com/emailAddress=email@example.com"
