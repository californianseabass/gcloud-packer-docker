# gcloud-packer-docker docker image
GCloud SDK + Packer. Meant for building and pushing images to google container registry. Also adds in jq in order to manipulate packer .json files, as well as jq to manipulate yaml files.

## Usage
```bash
docker pull californianseabass/gcloud-packer-docker:v0.0.2
```
californianseabass/gcloud-packer-docker

```bash
docker run -ti  californianseabass/gcloud-packer-docker:v0.0.2 -c "packer --version"
1.4.3
docker run -ti  californianseabass/gcloud-packer-docker:v0.0.2 -c "jq --version"
jq-1.6
```
