# Elasticsearch Exporter

Ansible role for provision Elasticsearch Exporter

## Requirements

ansible version >= 2.9

## Role Variables

```yaml
es_exporter_version: 1.1.0
es_exporter_web_listen_address: "0.0.0.0:9114"
es_exporter_web_telemetry_path: "/metrics"

es_exporter_es_url: "http://localhost:9200"

es_exporter_custom_option: ""

# for custom build
es_exporter_binary_local_dir: ""
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - be99inner.elasticsearch-exporter
```

## License

MIT

## Author Information

Anurak Janawan
