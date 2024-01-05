# deploy-example

settings: https://github.com/ohno/deploy-test/settings/secrets/actions

## FTP

https://github.com/ohno/deploy-test/blob/main/.github/workflows/ftp-deploy.yml

| variable | example |
| - | - |
| FTP_PASSWORD | `********` |
| FTP_SERVER | `****.sakura.ne.jp` |
| FTP_SERVER_DIR | `www` |
| FTP_USERNAME | `user` |

Reference:

- https://zenn.dev/hirof1990/articles/2f8eeab56b8637
- https://olein-design.com/blog/push-to-github-and-ftp-upload-to-server-at-the-same-time
- https://github.com/SamKirkland/FTP-Deploy-Action

## SSH

https://github.com/ohno/deploy-test/blob/main/.github/workflows/ssh-deploy.yml

