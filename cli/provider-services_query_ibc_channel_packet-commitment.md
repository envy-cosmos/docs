## provider-services query ibc channel packet-commitment

Query a packet commitment

### Synopsis

Query a packet commitment

```
provider-services query ibc channel packet-commitment [port-id] [channel-id] [sequence] [flags]
```

### Examples

```
<appd> query ibc channel packet-commitment [port-id] [channel-id] [sequence]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for packet-commitment
  -o, --output string   Output format (text|json) (default "text")
      --prove           show proofs for the query results (default true)
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
      --node string       The node address (default "http://localhost:26657")
```

### SEE ALSO

* [provider-services query ibc channel](provider-services_query_ibc_channel.md)	 - IBC channel query subcommands

###### Auto generated by spf13/cobra on 5-Dec-2022