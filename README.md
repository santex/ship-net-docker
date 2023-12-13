Docker Compose Jupyper
======================

# build 
```
docker-compose up -d
```

# RUN on container

```
python3.9 webspider.py -s c2 -e c2 -d 2 -c data -s c2 --in_filename data --out_filename data
python3.9 webspider.py -s c2 -e c2 -d 10 -c data -s c2 --in_filename data --out_filename data

```

# check

on 

```

http://localhost:5000/

```
