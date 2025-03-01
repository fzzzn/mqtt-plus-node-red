# MQTT + NODE-RED

## Install docker first

### Debian

```bash
curl -fsSL https://haste.zxn.my.id/raw/iculefeqij | bash
```

### Ubuntu

```bash
curl -fsSL https://haste.zxn.my.id/raw/isojurewob | bash
```

## Initializing

### Clone repository

```bash
git clone https://github.com/fzzzn/mqtt-plus-node-red
```

### Change directory

```bash
cd mqtt-plus-node-red
```

### Run the container

```bash
docker compose up -d
```

## MQTT

### Create mqtt user

```bash
sudo docker exec -it mosquitto mosquitto_passwd -c /mosquitto/passwd mqtt
```

## Node Red

Open http://`<your-ip>:1880 on web browser`
