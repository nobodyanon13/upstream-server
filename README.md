# upstream-server


#### Upstream Server

To setup the upstream server:
1. go to config.
2. Replace `<UPSTREAM-UUID>` in the `config.json` file with the generated UUID for the upstream server.
3. Run `docker-compose up -d`.



#### UUIDs

V2Ray uses the VMESS protocol as the primary protocol.
The VMESS protocol requires UUIDs for security reasons (instead of passwords).
We need two UUIDs for the two V2Ray servers (upstream and bridge servers).

You can generate UUIDs:

1- Online:

[https://www.uuidgenerator.net](https://www.uuidgenerator.net)
