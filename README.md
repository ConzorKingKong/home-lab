# Home Lab W NGINX Proxy Manager, Authentik, and Portainer

Run this command to create your `.env` file.

```bash
echo "PG_PASS=$(openssl rand 60 | base64)" >> .env
echo "AUTHENTIK_SECRET_KEY=$(openssl rand 60 | base64)" >> .env
```

Then add the following to your `.env` file

AUTHENTIK_BOOTSTRAP_PASSWORD=MAKE_A_ROOT_PASSWORD_HERE <br>
AUTHENTIK_ERROR_REPORTING__ENABLED=true
