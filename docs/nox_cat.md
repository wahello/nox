## nox cat

Query the cat apis

### Synopsis

JSON is great… for computers. Even if it’s pretty-printed,
trying to find relationships in the data is tedious. Human eyes,
especially when looking at an ssh terminal, need compact and aligned text.
The cat API aims to meet this need.

### Options

```
  -h, --help   help for cat
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

* [nox](nox.md)	 - Elasticsearch infrastructure management tool
* [nox cat aliases](nox_cat_aliases.md)	 - list configured aliases
* [nox cat allocation](nox_cat_allocation.md)	 - display shard allocation
* [nox cat count](nox_cat_count.md)	 - get document counts
* [nox cat fielddata](nox_cat_fielddata.md)	 - info on fieldata heap usage
* [nox cat health](nox_cat_health.md)	 - info on cluster health
* [nox cat indices](nox_cat_indices.md)	 - summary of all indices
* [nox cat master](nox_cat_master.md)	 - master node summary
* [nox cat nodeattrs](nox_cat_nodeattrs.md)	 - Shows custom node attributes
* [nox cat nodes](nox_cat_nodes.md)	 - Shows the cluster topology
* [nox cat pending_tasks](nox_cat_pending_tasks.md)	 - List pending tasks
* [nox cat plugins](nox_cat_plugins.md)	 - list plugins
* [nox cat recovery](nox_cat_recovery.md)	 - compact view of the JSON recovery API
* [nox cat repositories](nox_cat_repositories.md)	 - Shows the snapshot repositories registered in the cluster
* [nox cat segments](nox_cat_segments.md)	 - segment info
* [nox cat shards](nox_cat_shards.md)	 - shard info
* [nox cat snapshots](nox_cat_snapshots.md)	 - List snapshots in a repo
* [nox cat templates](nox_cat_templates.md)	 - Provides information about existing templates
* [nox cat thread_pool](nox_cat_thread_pool.md)	 - thread pool info

###### Auto generated by spf13/cobra on 6-Jun-2019