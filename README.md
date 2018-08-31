# api-blueprint-use-drakov

api blueprintとdrakovを利用してAPIモックサーバを立ち上げる


## Usage

```sh
> git clone https://github.com/kai-kou/api-blueprint-use-drakov.git
> cd api-blueprint-use-drakov
> npm install -g drakov
> drakov -f "md/*.md" --watch
> open http://localhost:3000/
```

use Docker

```sh
> git clone https://github.com/kai-kou/api-blueprint-use-drakov.git
> cd api-blueprint-use-drakov
> docker-compose up -d
> docker-compose exec api bash

>> drakov -f "md/*.md" --public --watch


# other Terminal
> open http://localhost:3000/
```
