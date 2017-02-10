## PHPLOC
[![Docker Pulls](https://img.shields.io/docker/pulls/rvannauker/phploc.svg)](https://hub.docker.com/r/rvannauker/phploc/) [![Docker Stars](https://img.shields.io/docker/stars/rvannauker/phploc.svg)](https://hub.docker.com/r/rvannauker/phploc/) [![](https://images.microbadger.com/badges/image/rvannauker/phploc:latest.svg)](https://microbadger.com/images/rvannauker/phploc:latest) [![GitHub issues](https://img.shields.io/github/issues/RichVRed/docker-phploc.svg)](https://github.com/RichVRed/docker-phploc) [![license](https://img.shields.io/github/license/RichVRed/docker-phploc.svg)](https://tldrlegal.com/license/mit-license)

Docker container to install and run phploc

### Installation / Usage
1. Install the rvannauker/phploc container:
```bash
docker pull rvannauker/phploc
```
2. Run phploc through the phploc container:
```bash
sudo docker run --rm --volume $(pwd):/workspace --name="phploc" "rvannauker/phploc" {destination}
```

### Download the source:
To run, test and develop the PHPLOC Dockerfile itself, you must use the source directly:
1. Download the source:
```bash
git clone https://github.com/RichVRed/docker-phploc.git
```
2. Build the container:
```bash
sudo docker build --force-rm --tag "rvannauker/phploc" --file phploc.dockerfile .
```
3. Test running the container:
```bash
 $ docker run rvannauker/phploc --help
```