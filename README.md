# devops

Shared devops scripts for syncing environment variables/secrets.

## Usage

```bash
pnpm exec sync-env-to-github --env=.env.production --environment=production
pnpm exec sync-env-to-aws --env=.env.production --environment=production
```

## Local development

```bash
# in this repo
pnpm install
pnpm link --global

# in a consumer repo
pnpm link --global @volpestyle/devops
```
