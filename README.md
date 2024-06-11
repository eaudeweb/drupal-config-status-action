# Deploy a release to the server

## Usage

```yml
steps:

  - uses: eaudeweb/drupal-config-status-action@1.x
    with:
      ssh_user:           ${{ secrets.TEST_SSH_USER }}
      ssh_host:           ${{ secrets.TEST_SSH_HOST }}
      ssh_key:            ${{ secrets.TEST_SSH_KEY }}
      ssh_user_jumphost:    ${{ secrets.TEST_SSH_USER_JUMPHOST }}
      ssh_host_jumphost:    ${{ secrets.TEST_SSH_HOST_JUMPHOST }}
      project_dir:        /var/www/html/www.example.com
```
