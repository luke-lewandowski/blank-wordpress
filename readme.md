# Basic WordPress Development Template #

It contains following

1. `docker-compose.yml` that will create following
   1. WordPress: [http://localhost:8080](http://localhost:8080)
   2. PHPMyAdmin: [http://localhost:8181](http://localhost:8181)
   3. MariaDB
2. Ensure that file uploads etc are set to 64MB (useful if you are getting large files or SQL backups restored).

## How to use ##

1. Setup your local environment - `docker-compose up -d`
2. Wait for it to spin up.
3. Load up WordPress and go through setup steps.
4. Start putting your themes or plugins in the `wp/plugins` or `wp/themes`.

Please don't use for production. Really.

## License ##

MIT

Enjoy!
