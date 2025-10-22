## 👋 Welcome to i2pd 🚀  

Description

### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/dfmgr/installer/raw/main/install.sh")" && sudo dfmgr install installer
```

### Install docker compose files

```shell
composemgr install i2pd
```

### Edit .env

```shell
$EDITOR "$HOME/.config/myscripts/composemgr/docker/$i2pd/.env"
```

### Edit app.env - will overwrite defaults from .env

```shell
$EDITOR "$HOME/.config/myscripts/composemgr/docker/$i2pd/app.env"
```

### Pull the containers

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$i2pd" pull
```

### Start the stack

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$i2pd" up &&
```

### Get the logs for the stack

```shell
composemgr --dir "$HOME/.config/myscripts/composemgr/docker/$i2pd" logs
```
