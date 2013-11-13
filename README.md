# Sendhub

NodeJS module to interact with the [Sendhub API][sendhub-api]

## Installation

```bash
npm install sendhub --save
```

## Methods

### sendhub.username

### sendhub.apiKey

### sendhub.createContact

### sendhub.listContacts

### sendhub.sendMessage

## Testing

```bash
grunt test
```

To run intergrations tests with sendhub,
append environment variables before `grunt test`

```bash
SENDHUB_USERNAME=1234567890 SENDHUB_APIKEY=apiKey SENDHUB_TEST_PHONE=+1234567890 grunt test
```


[sendhub-api]: http://apidocs.sendhub.com/
