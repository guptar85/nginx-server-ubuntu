#NGINX Configurations on Ubuntu

For Host key verification failed error -> ssh-keygen -R <ip_of_target_machine>

For available processes -> ps aux |grep nginx OR sudo systemctl status nginx

For nginx help -> nginx -h

C10K Problem -> https://en.wikipedia.org/wiki/C10k_problem

What is NGINX -> https://www.nginx.com/resources/glossary/nginx/

Building NGINX from Source -> http://nginx.org/en/docs/configure.html

NGINX systemd service file -> https://www.nginx.com/resources/wiki/start/topics/examples/systemd/

systemd and Serice manager -> https://www.freedesktop.org/wiki/Software/systemd/

NGINX Init Scripts -> https://www.nginx.com/resources/wiki/start/topics/examples/initscripts/

NGINX Configuration validation -> nginx -t

NGINX Pre-defined Variables -> http://nginx.org/en/docs/varindex.html

If used inside location context is not recommened -> https://www.nginx.com/resources/wiki/start/topics/depth/ifisevil/

HTTP status code -> https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

Rewrites will not change the URL. But redirect will change the URL

Try_files is superset of rewrites/ redirect. It mainly is used for 404 if resources not found

Logging -> https://docs.nginx.com/nginx/admin-guide/monitoring/logging/