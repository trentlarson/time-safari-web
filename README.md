
# Setup

`pkgx +vite sh`

# Develop

`vite serve`

# Build

`vite build`

# Deploy

`rsync --verbose --progress --stats --compress --recursive --times --perms --delete --exclude .git dist/* ...@...:www/timesafari.org`
