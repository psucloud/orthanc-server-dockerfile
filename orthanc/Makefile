orthanc:
	docker run -p 4242:4242 -p 8042:8042 --rm jodogne/orthanc
orthancupdate:
	docker pull jodogne/orthanc
orthancenabled:
	docker run -p 4242:4242 -p 8042:8042 --rm jodogne/orthanc-plugins
orthancgenconfig:
	docker run --rm --entrypoint=cat jodogne/orthanc /etc/orthanc/orthanc.json > /tmp/orthanc.json
orthancrestart:
	docker run -p 4242:4242 -p 8042:8042 --rm -v /tmp/orthanc.json:/etc/orthanc/orthanc.json:ro jodogne/orthanc