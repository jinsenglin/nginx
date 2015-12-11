# nginx

Proxy Server = Virtualbox Host

Proxy Server IP = 140.92.26.62

How to use this configuraiton
- Put file 'cert.pem' to your nginx server's /etc/nginx/
- Put file 'cert.key' to your nginx server's /etc/nginx/
- Modify file 'sites-available/default' to change ip '140.92.26.62' with your nginx server ip
- Put file 'sites-available/default' to your nginx server's /etc/nginx/sites-available/
- Restart your nginx server
