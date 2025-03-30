A collection of configuration examples providing the minimal information required for deployment of InfluxDB, Grafana and Telegraf.

Examples provided for `InfluxDB 1`, `InfluxDB 2` and `InfluxDB 3 Core (beta)`.

All paths shown assume you follow the vendor examples to create self-signed certificates. Adjust paths as needed.

> Warning: Self-signed certificates are not for production.  This is great for lab. However, adjust as needed to enforce certificate checking and use a CA instead if desired.

> Note: The examples for legacy `InfluxDB 1` shows using an example username and password. Adjust as needed.

> Tip: Ideally you shoud run `InfluxDB 2` or `InflluxDB 3`.

## Using `InfluxDB 3 Core (beta)`

For `InfluxDB 3 Core (beta)` follow the vendor instructions, which currently allows using a "token" of any value, or an empty string.

Also see the included hyper mike guide for InfluxDB 3 Core (beta). I walk you through the vendor instructions and do some other things like use PowerSHell to talk to InfluxDB using REST API.
