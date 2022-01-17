# docker-compose-sqlserver-ja

## Run container

```sh
UID_GID="$(id -u):$(id -g)" docker-compose up -d
```

## ConnectionStrings

```
Data Source=localhost;Initial Catalog=<dbname>;User ID=sa;Password=Password!;Integrated Security=True;Trusted_Connection=False;
```
