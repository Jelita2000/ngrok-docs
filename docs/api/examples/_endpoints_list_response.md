<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-15T10:06:22Z",
			"hostport": "a947de592b4e.ngrok.paid:443",
			"id": "ep_2qFTAoMIQgJPDlVEWP7T9K64huf",
			"name": "command_line",
			"principal": {
				"id": "usr_2qFT8GpUgYQJp9gKfXJkK1f2Gxn",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://a947de592b4e.ngrok.paid",
			"tunnel": {
				"id": "tn_2qFTAoMIQgJPDlVEWP7T9K64huf",
				"uri": "https://api.ngrok.com/tunnels/tn_2qFTAoMIQgJPDlVEWP7T9K64huf"
			},
			"tunnel_session": {
				"id": "ts_2qFTApVq29qe0J46u0kWft3p5P9",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qFTApVq29qe0J46u0kWft3p5P9"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-15T10:06:22Z",
			"upstream_url": "http://localhost:80",
			"url": "https://a947de592b4e.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-15T10:06:19Z",
			"domain": {
				"id": "rd_2qFTATjc9KzhBbzNbXwaN7tWP8r",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qFTATjc9KzhBbzNbXwaN7tWP8r"
			},
			"edge": {
				"id": "edgtls_2qFTARRKxHDXmYwyXLfBMtVQowP",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qFTARRKxHDXmYwyXLfBMtVQowP"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qFTAU9dHtfEHWOilfKxjx9seUd",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-15T10:06:19Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
