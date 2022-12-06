## provider-services query slashing params

Query the current slashing parameters

### Synopsis

Query genesis parameters for the slashing module:

$ <appd> query slashing params

```
provider-services query slashing params [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for params
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query slashing](provider-services_query_slashing.md)	 - Querying commands for the slashing module

###### Auto generated by spf13/cobra on 5-Dec-2022