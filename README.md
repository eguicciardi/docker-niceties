# Docker Niceties

Some simple useful docker compose files to get things going

## System Requirements

A system with Docker and *docker compose* installed and running properly and an internet connection to download images.

## Usage

You can use any nicety directly from its folder or feel free to copy/paste the content of the folder you need in your project main folder.

**Do not forget the *env.sample* file.**

To spin up a container:

```bash
docker compose up -d
```

The *-d* option is to run the container in detatched mode.

## List of niceties

This is a list of compose files included in the project along.

- Mysql Local

### Details

#### MySQL Local

This Docker Compose spins up a local MySQL server on the default port along with Adminer on the port 8080 for an easier administration.

