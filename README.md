# Reasoning service

Configurable reasoning service for the Harvester.
See [Eye Reasoning Service](https://github.com/eyereasoner/reasoning-service) for more information.


## Useage

```yaml
  reasoner:
    image: lblod/harvesting-reasoning-service
    restart: "no"
    volumes:
      - ./config/reasoner:/config
      - ./data/reasoner:/tmp
      - ./data/files:/share
```
