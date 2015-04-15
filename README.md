# SDCSB Cytoscape Advanced Tutorial
This repository is for course material for [SDCSB Advanced Cytoscape Workshop (4/17/2015)](http://sdcsb.ucsd.edu/cytoscape-and-network-analysis-workshop/)

Please read the [wiki](https://github.com/idekerlab/sdcsb-advanced-tutorial/wiki) for more information.

## Run the Notebook Server

For this tutorial, we will use [existing Docker image](https://registry.hub.docker.com/u/idekerlab/vizbi-2015/) used in the past workshop.

Make sure you have installed Docker properly.  Then type the following command:

```bash
docker run -d -p 80:8888 -v $PWD:/notebooks -e "PASSWORD=yourpw" -e "USE_HTTP=1" idekerlab/vizbi-2015
```

where ___yourpw___ is a password of your choice.  __This will take a LONG time when you run this command for the first time.__  Please try when you have stable and fast internet connection!

Now you can run the actual examples.  Don't forget to check the IP address of _boot2docker_ VM if you use Mac or Windows:

```bash
ᐅ boot2docker ip
192.168.59.103
```

In this case, you need to open ```http://192.168.59.103``` to access your notebooks.
