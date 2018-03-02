# rstweb-docker

This docker container allows you to build, install and run the
[rstWeb](https://corpling.uis.georgetown.edu/rstweb/info/)
Rhetorical Structure Theory annotation tool
(Zeldes 2016) in a docker container.

## Building / Installing / Running rstWeb directly from Docker Hub

The simplest way to run rstWeb 2.0.0 is to install [docker](https://www.docker.com/community-edition)
and then run the following command:

```
docker run -p 80:80 -ti nlpbox/rstweb
```

If you do this for the first time, it will take some time until the docker
container is downloaded. On later runs, rstWeb will start almost instantly.

After starting rstWeb, simply point your browser to [http://localhost/rstweb/](http://localhost/rstweb/).


# Citation

Zeldes, Amir (2016).
[rstWeb - A Browser-based Annotation Interface for Rhetorical Structure Theory and Discourse Relations](http://aclweb.org/anthology/N/N16/N16-3001.pdf).
In: Proceedings of NAACL-HLT 2016 System Demonstrations.
San Diego, CA, 1-5. 

