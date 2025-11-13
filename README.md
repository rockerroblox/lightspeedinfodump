## lightspeedinfodump
A short dump of information about Lightspeed Systems filters and products

- Written in Go.
- Using extensions, websockets, ports and extensions
- extensions aren't obfuscated
- Uses AWS and leaves creds in source code
- Has multiple vulns
- using domains. check OSN and also new domain: safetycheck-devices.relay.school
- main domain : devices.filter.relay.school
- agent-backend-api-production.lightspeedsystems.com
  Reads user/profile data of web browsers
  224.0.0.251:5353


  SEE TRIAGE REPORT AT https://tria.ge/251111-y5qshssjgt/behavioral1

Infinite new extension file: https://lsrelay-extensions-production.s3.amazonaws.com/chrome-filter/15ef5e1be7eac1c61563ca7c7562a8a54fda1c4571bafcb79e5fe908f8dd2f49/ChromeFilter.crx

Checks browser data via app telemetry. github.com/Lightspeed-Systems
has lots of private repos with valuable data, like LSConfigGo AlertAgent
