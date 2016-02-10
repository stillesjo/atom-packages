# atom-packages

## Install packages

```bash
curl https://raw.githubusercontent.com/stillesjo/atom-packages/master/packages | xargs apm install 
```

## Save packages

```bash
apm list --installed --bare | cut -d'@' -f 1
```
