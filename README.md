# paperless-ngx-coolify

Sets up paperless-ngx with postgresql, tika-support and syncthing.

docker-compose file for coolify.io

Set secrets
~~~
PAPERLESS_ADMIN_PASSWORD
PAPERLESS_ADMIN_USER
PAPERLESS_URL
~~~
from inside coolify.

Set ports and URLs in Coolify (8000 für paperless-ngx, 8384 for syncthing)

Consume directory is /var/syncthing/consume in syncthing.
