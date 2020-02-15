# marenbeam.com

This is the source for my personal site, accessible [here](https://marenbeam.com).

Changes to the site are automatically deployed by a once-per-hour cron job that runs on the server. The cron job simply clones the repo, and rsyncs the necessary things to `/var/www` so that nginx can serve them.

The server is an extremely vanilla debian box using nginx to serve content and certbot for SSL cert stuff.
