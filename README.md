# Simple application serveless with Lambda and DynamoDB

## Commands:

- configure serverless

```bash
  npm install -g serverless
```

- configure application

```bash
  npm install
```

- run insert table local

```bash
  sls invoke local -f hero-insert --path request-mock/hero.insert.json
```

- run trigger event local

```bash
  sls invoke local -f hero-trigger --path request-mock/hero.insert.json
```
