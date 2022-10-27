
### tunnel_group_backend_list.v0

| &nbsp; | &nbsp; | &nbsp; |
|---|---|---|
| id | string | unique identifier for this TunnelGroup backend |
| uri | string | URI of the TunnelGroupBackend API resource |
| created_at | string | timestamp when the backend was created, RFC 3339 format |
| description | string | human-readable description of this backend. Optional |
| metadata | string | arbitrary user-defined machine-readable data of this backend. Optional |
| labels | Map&lt;string, string&gt; | labels to watch for tunnels on, e.g. app->foo, dc->bar |
| id | string | a resource identifier |
| uri | string | a uri for locating a resource |
| uri | string | URI of the TunnelGroup backends list API resource |
| next_page_uri | string | URI of the next page, or null if there is no next page |