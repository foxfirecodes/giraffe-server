# giraffe-server

> tiny server config for a lil server i call "giraffe" (just for a few friends)

## setup

during first time setup you will want to run `get-env.sh` to initialize `.env` with the appropriate `UID` and `GID` values.

from there, it's just a matter of configuring some optional env vars if you want the Discord bot to work, namely:

## usage

just `docker compose up -d` from within the `giraffe-server` directory to start, `docker compose down` to stop

you can `docker compose attach mc` to access the interactive console. use <kbd>Ctrl-p Ctrl-q</kbd> to detach
