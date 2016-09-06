# FORK for testing purpose
This Dockerfile is forked for testing purpose. Please use original code by the link https://github.com/nik-kor/dockerfiles

# To run container:

```bash
docker run --name=ftp -v /home/spoonest/Documents/Projects/simple_downloader/tmp:/home/ftpusers/joe -p 21:21 -p 30000-30009:30000-30009 -d -e 'PUBLICHOST=localhost' spoonest/ftp
```

## User and password
Hardcoded:

    user: joe 
    password: 123456
