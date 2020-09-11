# DSpace version 5

```
docker-compose up --build
```

This will download all base images and dependencies then the source files will be build, so it will take some time to complete...

After previous command finishes, Dspace should be accessible via this url:
```
http://localhost:8080/jspui/
```

To exit containers use Ctrl+c in terminal where docker compose command was used

Then to delete columes and networks of the container use:

```
docker-compose down
```

.jsp files are stored in:
*dspace-jspui\src\main\webapp*

After editing the files, docker image needs to be rebuild with:

```
docker-compose up --build
```