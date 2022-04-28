
# Agrilink Backend Project 

Express JS API web-service that captures user contributed
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



## Run this project

Clone this project

```bash
  https://github.com/IamSahilvk/Agrilink.git
```

Then go to the project directory

```bash
  cd my-project
```

After that install dependencies

```bash
  npm install
```

Then start the server

```bash
  npm start
```



`CONNECTION_URL=""`

`PORT = 3000`






