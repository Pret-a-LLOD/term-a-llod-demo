
Term-a-LLOD
================================
A system for transforming and publishing terminologies as linked data which relies on a virtualization approach (i.e. docker). The system simplifies the transformation and hosting of terminological resources. As a proof-of-concept we publish and link the well-known IATE terminology as well as to various smaller terminologies. The program is written in java.

Installation
------------
install docker
docker build . -t debug:latest
docker run -p 8080:8080 -v ../server/:/tmp/server/ -v ../virtuoso_data/:/virtuoso_data/ -it debug:latest

User interface
------------
http://localhost/8080
```

```snapshot

```

The download status of each url of the `links.txt` file is transformed into a separate element. 

## pom.xml
The POM contains all related dependencies

## dependencies
The program is tbx2rdf project developed in LIDER project as dependency (https://github.com/cimiano/tbx2rdf)


## Author
* **Mohammad Fazleh Elahi**
* **Frank Grimm**
* **Philipp Cimiano**
