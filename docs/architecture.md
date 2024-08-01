# Architecture

Calmseek is a cloud-native distributed search system for AI applications. 

* decoupled compute and storage
* multitenant
* multimodal
* multilingual

## data model

tenant/namespace

document, text, high-dimensional vectors

### schema management

semi-schemaless, only indexed fields need to be defined

sparse fields - any field can be missing

automatic detection and addition of new indexed fields

## separation of compute and storage

### private cloud deployment

built on cubefs

### public cloud deployment



