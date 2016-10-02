# apache2-ssl-config
Sample config files for setting up apache2 with SSL. 

This configuration uses the method of redirecting on port 80 -> port 443, rather than blocking port 80 altogether. Furthermore, the redirection goes from http\* to https://www\* to force all traffic on port 443 with the www subdomain.
