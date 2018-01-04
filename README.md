# TrumpCloud

I was wondering around the internet and found this http://www.trumptwitterarchive.com/ . My natural inclination was word cloud

# build and run with docker

```
docker build -t trumpcloud -f Dockerfile.trumpcloud .
```

then

```
docker run -p 8888:8888 trumpcloud
```

lastly go to

http://0.0.0.0:8888/notebooks/TrumpWordCloud.ipynb

to run this notebook