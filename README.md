# steamcmd-arm
ARM docker image that runs SteamCMD through box86. Default entry point is `steamcmd +help +quit`.

## Tags
* **`debian-11`** (*[debian-11/Dockerfile](debian-11/Dockerfile)*)
* `debian-11-slim` (`docker-slim build --target weilbyte/steamcmd-arm:debian-11 --tag weilbyte/steamcmd-arm:debian-11-slim --exec "steamcmd +help +quit" --http-probe=false`) (*Experimental*)

> `debian-11-slim` variant is the standard `debian-11` image ran through `docker-slim`. This image is very minimal and doesn't even have coreutils.

## License
This repository is licensed under MIT.