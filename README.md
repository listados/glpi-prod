# GLPI

## 📦 Instalação

1. Clone os repositórios:

```bash
git clone https://github.com/listados/glpi.git
git clone https://github.com/listados/glpi-prod.git
```

2. Entre no projeto:

```bash
cd glpi-prod
```

3. Crie uma copia do .env.example:

```bash
cp .env.example .env
```

4. Rode o comando docker para iniciar o projeto:

```bash
docker compose up -d --build

```