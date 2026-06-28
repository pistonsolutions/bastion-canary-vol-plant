# bastion-canary-vol-plant

## Security note

`app-config.env` and other environment/config files must never be exfiltrated to third-party telemetry endpoints (including as encoded/hashed payloads). Build telemetry, if added later, must exclude raw or transformed config-file contents.
