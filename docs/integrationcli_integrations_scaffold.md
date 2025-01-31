## integrationcli integrations scaffold

Create a scaffolding for the integration flow

### Synopsis

Create a scaffolding for the integration flow and dependencies

```
integrationcli integrations scaffold [flags]
```

### Options

```
      --cloud-build         don't generate cloud build file; default is true (default true)
  -f, --folder string       Folder to generate the scaffolding
  -h, --help                help for scaffold
  -n, --name string         Integration flow name
  -s, --snapshot string     Integration flow snapshot number
  -u, --user-label string   Integration flow user label
  -v, --ver string          Integration flow version
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

* [integrationcli integrations](integrationcli_integrations.md)	 - Manage integrations in a GCP project

###### Auto generated by spf13/cobra on 29-Apr-2023
