Orthanc Docker Startup (Needs Docker, Compose)
-------
# `cd orthanc` into this directory
### Startup (using docker-compose):
`docker-compose up`

### Individual Makefile Quickstart:
- `make orthanc` for quickstart
- `make orthancupdate` to grab recent dockerfile
- `make orthancenabled ` to run with plugins
- `make orthancgenconfig` to generate a new config file
- /tmp/orthanc.json has the config file
- `make orthancrestart` to restart after config file updates 
