# tailscale-sidecars

A list of docker compose yaml configuration that leverage tailscale as a sidecar.  All of these containers have the following prerequisites:

- A generated TS_AUTHKEY from Tailscale
- A `container` tag added to your Access Controls
```
"tagOwners": {
		"tag:container": ["autogroup:admin"],
	},
```
