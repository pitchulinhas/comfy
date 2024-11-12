# Authorization Server

Comfy's authorization server.

## Configuration

To run the authorization server you need to set the environment variables below in your system:

- **AUTHORIZATION_SERVER_DB_NAME**: Name of the database to store app data;
- **AUTHORIZATION_SERVER_DB_USER**: Database admin username;
- **AUTHORIZATION_SERVER_DB_PASS**: Database admin password;
- **AUTHORIZATION_SERVER_DB_EXTERNAL_PORT**: Database port to external access;
- **AUTHORIZATION_SERVER_APP_ADMIN_USER**: Application admin username;
- **AUTHORIZATION_SERVER_APP_ADMIN_PASSWORD**: Application admin password;
- **AUTHORIZATION_SERVER_APP_DB_VENDOR**: Database vendor (e.g. postgres);
- **AUTHORIZATION_SERVER_APP_DB_URL**: JDBC database url;
- **AUTHORIZATION_SERVER_APP_DB_USER**: Database admin username;
- **AUTHORIZATION_SERVER_APP_DB_PASS**: Database admin password;
- **AUTHORIZATION_SERVER_APP_EXTERNAL_PORT**: Application port to external access.

**If You are in doubt You can find a .env example file in authorization server folder.**

## Running

To run the application you just need to run the command below in authorization server folder on the terminal:

```shell
sudo docker compose up -d
```

To stop the application you can run the command below in authorization server folder on the terminal:

```shell
sudo docker compose down
```
