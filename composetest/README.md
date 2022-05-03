# Compose Test

A simple Python web application running on Docker Compose.

## Run Locally

Go to the project directory

```bash
  cd composetest
```

Start the application

```bash
  docker compose up
```

Enter http://localhost:8000/ into a browser to confirm the applcation is running. You should see this message in your browser: 

```txt
  Hello World! I have been seen 1 times.
```

Try refreshing the browser to confirm the visit counter increases by 1

Stop the application

```bash
  docker compose down
```

