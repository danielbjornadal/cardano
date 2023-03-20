# Cardano Metadata
Host your own metadata in Kubernetes with Nginx and Configmap.
```
cardano-cli stake-pool metadata-hash --pool-metadata-file <(curl -s -L -k https://<yourpool>/pool.json)
```