# Architecture

Calmseek is a cloud-native distributed search system for AI applications. 

* decoupled compute and storage
* multitenant
* multimodal
* multilingual

## data model

tenant/namespace

document, text, high-dimensional vectors

## schema management

semi-schemaless, only indexed fields need to be defined

sparse fields - any field can be missing

automatic detection and addition of new indexed fields

## storage layer

### private cloud deployment

built on cubefs

### public cloud deployment

WAL on cubefs

data + index files can be persisted onto cloud storage such as S3

## multitenancy

each tenant has a dedicated namespace

one node can serve tens of thousands active tenants, dynamically loading active namespaces or offloading inactive ones



