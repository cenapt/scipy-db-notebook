# scipy-db-notebook

Based on https://hub.docker.com/r/jupyter/scipy-notebook it adds:

- DB support for Postgres (sqlalchemy), Mongo (pymongo)
- Bio (BioPython and openbabel)
- Semantic web (rdflib, rdflib-jsonld)
- AWS/S3 support (boto3)
- Textmining (nltk)

## Basic use

docker run -it --rm -p 8888:8888 cenapt/scipy-db-notebook

