# For Testing ONLY

## How To:
Run: `node node_modules/cas-server-mock/server.js --port=3004 --database=${PWD}/users.json`

Update Local Ilios config with:

```
ILIOS_AUTHENTICATION_TYPE=cas
ILIOS_CAS_AUTHENTICATION_SERVER=http://localhost:3004
ILIOS_CAS_AUTHENTICATION_VERIFY_SSL=false
ILIOS_CAS_AUTHENTICATION_VERSION=3
```
