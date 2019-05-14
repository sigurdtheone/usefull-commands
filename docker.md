Get Jenkins initial admin password from docker container.

```bash
docker exec -ti jenkins sh -c "cat /var/jenkins_home/secrets/initialAdminPassword"
```
