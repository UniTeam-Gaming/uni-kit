# kit-blog

This module is the blog module of the website. For now, this module is containing the necessary to test Grav CMS.

## How to test

### Windows
Install Docker Desktop on your computer. Open a terminal in this current folder. If the folder grav-data doesn't exist 
create it with the following command :
```bash
mkdir grav-data
```

And then, start the containers:
```bash
docker-compose up -d
```
It will create a grav-data folder and start the kit-blog project with a Grav CMS container.

Just go to http://localhost:8080 to see the result.