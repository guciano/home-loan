## Prerequisite

To run this program, you will need

### App Dependencies

```$xslt
- Golang 1.16+
- Go mod enabled
```

## How to Run

### Setup Config

```
cp .env.example .env
```

### Run Application

```
make run
```

## How to Test

```
make test
```

## How to Lint

```
make lint
```

## Deployment

### Build

```
make build
```

## Configuration

| NAME | DESCRIPTION | TYPE | VALUE
| ------ | ------ | ------ | ------ |
| APP_NAME | Application name | string | alphabet |
| APP_PORT | Application port | int | number |
| JWT_SECRET_KEY | JWT Secret | string | alphabet |
