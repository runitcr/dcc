# Image

Ansible role to pull or build a Docker image and optionally upload it to Dockerhub.

For more information see [collection's README](../../README.md).

## Index

- [Variables](#variables)
- [License](#license)
- [Author](#author)

## Variables

Supported variables are displayed along with
their default values (*./defaults/main.yml*):

```
docker_image_build: true
docker_image_name: 'runitcr/dcc'
docker_image_repository: https://github.com/runitsolutions/DCC.git
docker_image_repository_branch: 'version-1.3.5'
dockerhub_image_pull: false
dockerhub_user: 'runitcr'
dockerhub_password: 'mySuperHubPassword'
dockerhub_mail: 'runitcr@guerrillamail.com'
dockerhub_image_push: false
```

## License

MIT.

## Autor

![Runitcr](../../img/author.png)

[Runitcr](https://runitcr.com).