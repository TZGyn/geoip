# GeoIP

## A maxmind geoip api server with auto db refresh

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/LiUOsa?referralCode=bSruGU)

## Deployment

```bash
go build main.go # compile
ACCOUNT_ID={id} LICENSE_KEY={key} ./main # run
```

## Development

```bash
air # with air
go run main.go # without air
```

## API

https://geoip.fly.dev/{ip}
https://geoip.fly.dev/me
