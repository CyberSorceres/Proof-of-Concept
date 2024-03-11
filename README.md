# Proof-of-Concept

## Prima esecuzione

### Backend

```
- cd poc_backend
- npm i g- serverless
- npm i
- serverless offline start
```
- Installare WAS CLI: [https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html]

-```aws configure```
- AWS Access Key ID [****************VNGP] ```DEFAULT_ACCESS_KEY```
- AWS Secret Access Key [****************ROhl] ```DEFAULT_SECRET```
- Default region name [eu-central-1] ```eu-central-1```
- Default output format: invio

### Frontend

```
- cd poc_frontend
- npm i
- npm start
```

### Plug-in

```
- cd poc_plugin
- npm i
```
- In VSCode premere F5

## Esecuzioni successive

### Backend

```
- serverless offline start
```

### Frontend

```
- npm start
```

### Plug-in

- In VSCode premere F5

## Testing

### Plug-in

- Creare un nuovo file .js
- Incollare il seguente codice:
```
@PROJECT-123

@USERSTORY-1
65e2f1f44f87e6edd1a3fa4d
@USERSTORY-END

@USERSTORY-2
65e35137c1943b021d5697e2
@USERSTORY-END
```
- Premere CTRL + Shift + P
- Selezionare: Genera test
- Una volta generati i test Premere CTRL + Shift + P
- Selezionare: Run test
