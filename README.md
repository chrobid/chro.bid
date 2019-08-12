# chro.bid

This is the source code for my personal website, which you can visit at https://www.chro.bid

Changes to the site are automatically "deployed" by a cron job on the server that runs once per hour. The cron job simply clones the repo, and rsyncs the necessary things to `/var/www` so that nginx can serve them.
