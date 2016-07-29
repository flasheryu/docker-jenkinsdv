# docker-jenkinsdv

Packages the jenkins configuration backups as a data volume in a docker container.

## Example usage

```bash
docker run --name jenkinsDV flasheryu/jenkinsdv
```

## Note
The jenkins_home directory should contain all the configurations from your backup jenkins project.