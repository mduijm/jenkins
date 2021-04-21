# Jenkins

Place to store YAML files to build custom Jenkins image for FortiPoc

download Dockerfile + plugins.txt + casc.yaml

run: 
`
docker build -t jenkins:jcasc .
docker images
docker tag <image id> fortinetdemo/jenkins:jcasc
docker push fortinetdemo/jenkins:jcasc
`
The image is base on the latest Jenkins 
