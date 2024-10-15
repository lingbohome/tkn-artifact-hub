# tkn-artifact-hub
shipper 的 tkn artifact,包括 task 和 pipeline


### 推送artifact到OCIRegistry

```
tkn bundle push hub.cloud.lingbohome.com/shipper/tkn-artifacts/catalog/builtin:0.1 -f .\git-clone.yaml
```

### 从OCIRegistry列出artifact

```
tkn bundle list hub.cloud.lingbohome.com/shipper/tkn-artifacts/catalog/builtin:0.1
```