Swagger UI com RHSSO Admin REST API

Execute o script `run.sh`

```
chmod +x run.sh
./run.sh
```

Para alterar o endpoint / server do RHSSO altere o arquivo `srv/18.0.json`

```
  "servers": [
    {"url": "http://SERVER:PORT/auth/admin/realms"}
  ],
```

> O valord default é http://localhost:8080/auth/admin/realms


Especificação [ccouzens/keycloak-openapi](https://github.com/ccouzens/keycloak-openapi/). Obrigado!