## Docker Cheat Sheet

### Docker-machine

Docker-machine will help to provision new docker hosts on different cloud platform. If you are lazy to install docker-engnine from the scratch for every machine you provision then this is the right tool for you.

### Provisioning machine on the Digital Ocean Cloud provider
```markdown
$docker-machine create --driver digitalocean \
      --digitalocean-access-token <token> <name of the machine>
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

