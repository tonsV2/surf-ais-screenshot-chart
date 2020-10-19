# TODO
* deployment-nginx: Use initContainer to create /data/uploads on pv... mkdir -p /data/uploads
* values.yaml: Group all job related values under a job key. Similar to what's done with nginx and selenium

# Release
```bash
./gradlew release
```

# Development
```bash
skaffold dev
```
