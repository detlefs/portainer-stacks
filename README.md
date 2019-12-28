# Portainer Compose YAML files

These YAML files are used to deploy all services used on my private home server.

Currently the following services/apps are contained:

- Duplicati

    Duplicati is a backup client that securely stores encrypted, incremental, compressed backups on local storage, cloud storage services and remote file servers.

- Emby Server

    Emby, formerly Media Browser, is a media aggregator plugin for Media Center that takes your recorded, digital, or ripped media and presents it in a simple, easy to use web interface.
    The stack includes also EmbyStat

- Heimdall

    As the name suggests Heimdall Application Dashboard is a dashboard for all your web applications. It doesn't need to be limited to applications though, you can add links to anything you like.

- NodeRED
  
    Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

- mitmproxy

    [mitmproxy](https://mitmproxy.org) is an interactive network packages analyzing proxy with a web UI. mitmproxy in this stack configures the proxy to listen on port `8080` and the web UI to be accessible via [http://[ip-address]:8081](http://[ip-address]:8081)
