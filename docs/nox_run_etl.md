## nox run etl

Run a manual reindex with an extra data transform step

### Synopsis

This command essentially performs a manual document reindex on an Elasticsearch cluster.
What makes this different is that you can perform a data transform step before the data is saved to the index.
This allows for Elasticsearch data ETL between indicies, and to new indices.

```
nox run etl [source_index] [flags]
```

### Options

```
      --batch int            size of thethe batches of documents per scroll (default 1000)
      --destination string   destination index name, defaults to source index
      --dry-run              toggle dry run for etl command
      --fields string        comma seperated list of fields you want to retrieve from the _source object on search
  -h, --help                 help for etl
      --scroll string        how long to keep the scroll context alive (default "1m")
      --threads int          number of slices/threads to split the scroll into (default 2)
```

### Options inherited from parent commands

```
      --config string     config file (default is $HOME/nox.yaml)
  -d, --debug             toggle debug setting
  -H, --host string       host of your elasticsearch cluster (default "localhost")
  -W, --password string   password for authentication with the cluster
  -p, --port string       port for communication with your elasticsearch cluster (default "9200")
      --pretty            toggle pretty printing of returned json (default true)
      --silent            toggle silent output
  -t, --tls               use TLS for cluster connections
  -u, --username string   username for authentication with the cluster
```

### SEE ALSO

* [nox run](nox_run.md)	 - run a generic operation

###### Auto generated by spf13/cobra on 31-May-2019