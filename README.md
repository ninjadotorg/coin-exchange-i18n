# Coin Exchange i18n

A special thank to [Crowdin](https://crowdin.com/) for help us use their tool for translate everything on [Coin-Exchange](https://github.com/ninjadotorg/coin-exchange-i18n) project (https://crowdin.com/project/coin-exchange) at no cost.

## Install

```
yarn
```

## Run

### All of process

```
yarn i18n
```

### Build parsed file need to i18n

```
yarn i18n-prepare
```

### Send to Crowdin

```
yarn send
```

### Build translated file and re-parsed

```
yarn handle-i18n-ed
```

## Misc notes

```
git submodule init
git submodule add https://github.com/ninjadotorg/coin-exchange-i18n.git app
git submodule update
git submodule foreach git pull origin develop
```
