<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-15T10:06:30Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qFTBtWUWhwuxsR719owtrPqNrA",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qFTBtWUWhwuxsR719owtrPqNrA"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qFTAV5eQmFLeYuyHSzRtGLe15J",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qFTAV5eQmFLeYuyHSzRtGLe15J"
				},
				"enabled": true
			},
			"created_at": "2024-12-15T10:06:19Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qFTARRKxHDXmYwyXLfBMtVQowP",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qFTARRKxHDXmYwyXLfBMtVQowP"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
