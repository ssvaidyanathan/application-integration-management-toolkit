## integrationcli authconfigs create

Create an authconfig

### Synopsis

Create an authconfig

```
integrationcli authconfigs create [flags]
```

### Options

```
  -e, --encrypted-file string     Base64 encoded, Cloud KMS encrypted Auth Config JSON file path
  -k, --encryption-keyid string   Cloud KMS key for decrypting Auth Config; Format = locations/*keyRings/*/cryptoKeys/*
  -f, --file string               Auth Config JSON file path
  -h, --help                      help for create
```

### Options inherited from parent commands

```
  -a, --account string   Path Service Account private key in JSON
      --api api          Sets the control plane API. Must be one of prod, staging or autopush; default is prod
      --disable-check    Disable check for newer versions
      --no-output        Disable printing all statements to stdout
      --print-output     Control printing of info log statements (default true)
  -p, --proj string      Integration GCP Project name
  -r, --reg string       Integration region name
  -t, --token string     Google OAuth Token
      --verbose          Enable verbose output from integrationcli
```

### SEE ALSO

* [integrationcli authconfigs](integrationcli_authconfigs.md)	 - Manage integration auth configurations

###### Auto generated by spf13/cobra on 29-Apr-2023
