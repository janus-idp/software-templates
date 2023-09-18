# Register existing component to Service Catalog

This template is intended to be used as a starting point for registering an existing repository to the Service Catalog.

Currently, it only supports repositories hosted on Gitlab (both `gitlab.com` and Gitlab for Enterprise are supported).

## Required Gitlab permissions

- The Gitlab access token needs to have `api` read & write scopes and added to your gitlab integration
- If using a private Gitlab instance, please make sure the `apiBaseUrl` is set correctly:

    ```yaml
    integrations:
      gitlab:
        - host: gitlab.mycompany.com
          token: my-gitlab-token
          apiBaseUrl: https://gitlab.mycompany.com/api/v4
    ```
