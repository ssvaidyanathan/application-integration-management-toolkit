## integrationcli authconfigs export

Export authconfigs in a region to a folder

### Synopsis

Export authconfigs in a region to a folder

```
integrationcli authconfigs export [flags]
```

### Options

```
  -f, --folder string   Folder to export authconfig
  -h, --help            help for export
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
