FROM fernandomj90/alura-sistema-teste2

CMD sudo chgrp -R www-data /var/www/html/
CMD sudo chown -R www-data /var/www/html/
CMD sudo chmod -R g+w /var/www/html/
CMD find /var/www/html/ -type d -exec chmod g+s {} + 
CMD sudo chown -R www-data /tmp

ENTRYPOINT /bin/bash

USER www-data
