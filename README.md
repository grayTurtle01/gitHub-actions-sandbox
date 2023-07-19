# gitHub-Actions Sandbox 🧪 

## Triggers all push
```
on: push
```

## Triggers on branch push
```
on:
  push:
    branches:
       - main
       - dev

```
```
on:
  push:
    branches: [main, dev]

```
## On pull request
```
on:
  pull_request:
    branches: [ main ]
```
