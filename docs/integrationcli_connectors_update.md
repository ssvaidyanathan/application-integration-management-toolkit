## integrationcli connectors update

Update an existing connection

### Synopsis

Update an existing connection in a region

```
integrationcli connectors update [flags]
```

### Options

```
  -f, --file string               Connection details JSON file path
  -h, --help                      help for update
  -n, --name string               Connection name
      --update-mask stringArray   Update mask: A list of comma separates values to update
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

* [integrationcli connectors](integrationcli_connectors.md)	 - Manage connections for Integration Connectors

###### Auto generated by spf13/cobra on 29-Apr-2023
