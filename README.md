# wordpress docker compose


<div>
<img  src="https://upload.wikimedia.org/wikipedia/commons/9/98/WordPress_blue_logo.svg"  width="150px"  height="150px">
<img  src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg"  width=""  height="150px">
</div>
  
  

to have your own wordpress server you need to run the following command

  

```console

docker-compose -f "docker-compose.yml" up -d --build
docker run -d -p 3000:3000 --name metabase metabase/metabase

```

  
  

is a docker compose to create a complete containerized solution for WordPress, it contains a mysql container and an ubuntu container that runs apache and php, made for a university task




# csv to docker mysql
<div>
<img  src="https://upload.wikimedia.org/wikipedia/commons/c/c6/.csv_icon.svg"  width="150px"  height="150px">
<img  src="https://www.exa.unicen.edu.ar/sites/default/files/docker-logo.png" width="200px">
</div>

if you want to work with a csv like a database you only need 

## Download
```console
git clone https://github.com/lukaneco/csv-to-docker-mysql.git
cd csv-to-docker-mysql
```
## Setup data
copy a csv to the folder scripts
#### Windows
 ```console
run.ps1
```
#### Ubuntu
 ```console
run.sh
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNjAyMDk1MzIsLTgxODYyODU3MywxNz
Q5Mzg1NzQ1LDU3MDAxMDA2NCwtNjYwMzU2OTQwLC0yNjIyMDQ2
MTksLTUxNDQwNDk3NywxNjY0MDkwMDE3XX0=
-->
