# nexus-aarch64
### Create the volume and start eh container


`docker volume create --name nexus-data`

`docker run -d -p 8081:8081 --name nexus -v nexus-data:/nexus-data ankursingh081/nexus-aarch64`

