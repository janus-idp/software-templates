# GitHub Actions CI Method

## Requirements

The GitHub Actions CI Method will require repository secrets setup before GitHub Actions can run

CI Secrets

- `REGISTRY_NAMESPACE` - The Quay.io registry namespace you wish to push the image to ex. quay.io/<IMAGE_NAMESPACE>/<IMAGE_NAME>:Tag
- `REGISTRY_USERNAME` - The Quay.io registry username for the bot
- `REGISTRY_PASSWORD` - The Quay.io registry password for the bot
