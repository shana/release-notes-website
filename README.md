## Release notes generator for the visualstudio.github.com website

To make this work, you need to:

- Create an application on github.com
- Set the following environment variables:

```
APP_NAME="Name of application"
APP_CLIENT_ID=application-client-id
APP_CLIENT_SECRET=application-client-secret
```

This script will try to login for you, with 2FA. If that fails or you don't want to use 2FA, do the following to set the credentials:

- Create folder `scratch`
- Create file `scratch\user` with the username
- Create file `scratch\token` with a personal token