

Template example for a ecommerce analytics project using Tinybird

## Install

First install tinybird cli, you'd need python3 installed

```
pip install tinybird-cli
```

then run:

```
tb auth
``` 

You have to paste your admin token to authenticate

```
tb push --push-deps --fixtures
tb push pipes/top_product_per_day.pipe --populate --force
```

Ready to use in your tinybird account
