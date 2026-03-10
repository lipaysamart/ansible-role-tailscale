## Requirements

N/A

## Role Variables

```sh
tailscale_auth_key: ""
tailscale_up_options: ""
```

## Dependencies

None

## Example Playbook

```yml
- hosts: localhost
  roles:
    - lipaysamart.tailscale
  vars:
    tailscale_up_options: "--accept-routes"
```

## License

MIT
