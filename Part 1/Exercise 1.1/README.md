# Exercise 1.1

## Commands

```bash
docker container run nginx (x3)

docker container stop sleepy_kalam
docker container stop relaced_archimedes

docker container ls -a
```

## Terminal - Containers list

```bash
Script started on 2024-04-01 21:51:29+01:00 [TERM="xterm-256color" TTY="/dev/pts/6" COLUMNS="192" LINES="19"]
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS                     PORTS     NAMES
108cc4287e17   nginx     "/docker-entrypoint.…"   7 minutes ago   Exited (0) 5 minutes ago             sleepy_kalam
bb09a0906e23   nginx     "/docker-entrypoint.…"   7 minutes ago   Exited (0) 5 minutes ago             relaxed_archimedes
c0e2a3e9a771   nginx     "/docker-entrypoint.…"   8 minutes ago   Up 8 minutes               80/tcp    fervent_chaum
```