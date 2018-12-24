## Couchdb Grafana Data Source Plugin

## Installation

To install this plugin using the `grafana-cli` tool:
```
sudo grafana-cli plugins install couchdb-datasource
sudo service grafana-server restart
```

### Dev setup

This plugin requires node 6.10.0

```
npm install -g yarn
yarn install
npm run build
