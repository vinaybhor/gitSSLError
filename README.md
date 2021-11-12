# gitSSLError
Unable to clone remote repository: SSL certificate problem: self signed certificate in certificate chain


1. Copy Base64 encoded certificate from browser to a cer file.
2. Configure git to trust this certificate
$ git config --global http.sslCAInfo \Downloads\Devops.cer
