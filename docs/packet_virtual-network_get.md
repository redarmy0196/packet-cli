## packet virtual-network get

Retrieves a list of virtual networks for a single project.

### Synopsis

Example:

packet virtual-network get -p [project_UUID]

	

```
packet virtual-network get [flags]
```

### Options

```
  -h, --help                help for get
  -p, --project-id string   UUID of the project
```

### Options inherited from parent commands

```
      --config string     Path to JSON or YAML configuration file
      --exclude strings   Comma seperated Href references to collapse in results, may be dotted three levels deep
      --include strings   Comma seperated Href references to expand in results, may be dotted three levels deep
  -j, --json              JSON output
      --search string     Search keyword for use in 'get' actions. Search is not supported by all resources.
  -y, --yaml              YAML output
```

### SEE ALSO

* [packet virtual-network](packet_virtual-network.md)	 - Virtual network operations

