```YAML
nginx: 
  image: nginx:1.12.1 
  restart: always 
  logging: 
    driver: "json-file"
    options: 
      max-size: "5g"
```
