# Docker Installation Guide

### Useful Docker Commands
- Check status of current running services
```cmd
docker stats
```
- Remove all existing services
	- but it'll also remove persistant (local) volumnes that I stored connections/variables/airflow acc info
```
docker compose down --volumes --remove-orphans
```