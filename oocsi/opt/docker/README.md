# OOCSI web

Distribution bundle for OOCSI web server with web socket support and other functionalities for using OOCSI on the web. To use, please  extract the release zip into a folder, adjust permissions on bin/oocsi-websocket (`chmod a+x bin/oocsi-websocket`), then execute the launcher (`./bin/oocsi-websocket`).

Web socket connections can connect to `/ws`, a simple dashboard is available from `/dashboard`.

To start the server on a different port than the default 9000, use the addtional `-Dhttp.port=<port>` command line option.
