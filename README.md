## Docker Cheat Sheet

### Docker-machine

Docker-machine will help to provision new docker hosts on different cloud platform. If you are lazy to install docker-engnine from the scratch for every machine you provision then this is the right tool for you.

## Provisioning machine on the Digital Ocean Cloud provider

### Create new node in digitalOcean
```markdown
$docker-machine create --driver digitalocean \
      --digitalocean-access-token <token> <name of the machine>
```

### SSH to the node
```markdown
$docker-machine ssh <node>
```
### list the node ip address
```markdown
$docker-machine ip <node>
```
### List the nodes
```markdown
$docker-machine ls
```
### Stop the node
```markdown
$docker-machine stop <node>
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

