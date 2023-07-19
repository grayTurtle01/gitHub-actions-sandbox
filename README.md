# gitHub-Actions Sandbox 🧪 

## Hello gitHub Actions
```
name: My First WorkFlow
on: 
  push:
    branches: [ main ]
       
jobs:
  task_0:
  
    runs-on: ubuntu-latest

    steps:
 
      - name: Greetings with echo
        run: echo "Hello gitHub actions"
      

```


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
