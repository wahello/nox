## nox snapshot start

Kick off a snapshot

### Synopsis

Kick off a snapshot

```
nox snapshot start [name] [flags]
```

### Options

```
  -b, --body string    json body to send with this request
  -h, --help           help for start
  -n, --notify         Send notification to slack
  -s, --slack string   Slack webhook to send snapshot failures to
  -w, --wait           Wait for completion of snapshot
```

### Options inherited from parent commands

```
      --config string      config file (default is $HOME/nox.yaml)
  -d, --debug              toggle debug setting
  -f, --frequency string   Frequency of the snapshot
  -H, --host string        host of your elasticsearch cluster (default "localhost")
  -W, --password string    password for authentication with the cluster
  -p, --port string        port for communication with your elasticsearch cluster (default "9200")
      --pretty             toggle pretty printing of returned json (default true)
  -r, --repo string        Repository for the snapshot
      --silent             toggle silent output
  -t, --tls                use TLS for cluster connections
  -u, --username string    username for authentication with the cluster
```

### SEE ALSO

* [nox snapshot](nox_snapshot.md)	 - tool for managing snapshots

###### Auto generated by spf13/cobra on 18-Jun-2019