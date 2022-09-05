# amp-telemetry-plugin
Telemetry plugin for Azure Media Player (AMP). The goal is to ensure a good user experience.

## TL;DR:
* Install [caddy](https://caddyserver.com/docs/install), on Windows the easiest way would be to use [chocolatey](https://chocolatey.org/install):
``` 
$> choco install caddy 
```
* Clone the repository:
```
$> git clone git@github.com:Jynsaillar/amp-telemetry-plugin.git
```
* CD into the project directory:
```
$> cd amp-telemetry-plugin
```
* Checkout the devel branch:
```
$> git checkout devel
```
* cd into the /src/ folder:
```
$> cd ./src
```
* Run caddy (it should load the Caddyfile automatically):
```
$> caddy run
```
Now, the test page should be available on https://localhost:2525/testDev.html
