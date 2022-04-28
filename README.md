
# Agrilink Project

Express JS API web-service which captures user contributed
reports and returns an aggregate report in response.


## API Reference

#### Post One Report

```http
  POST /reports
```

#### Get Report

```http
  GET /reports/${reportID}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. reportID of report to fetch |



## Run Locally

Clone the project

```bash
  https://github.com/IamSahilvk/Agrilink.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```
Now open postman and test with data



`CONNECTION_URL=""`

`PORT = 3000`






