# Architecture

Calmseek is a cloud-native distributed search system for AI applications. 

* decoupled compute and storage
* multitenant
* multimodal
* multilingual

## data model

cluster, tenant/namespace, document, field

semi-schemaless, only indexed fields need to be defined

sparse fields - any field can be missing

automatic detection and addition of new indexed fields

## storage layer

local filesystems, or cubefs

## server components

calmserver, calmkeeper, calmrouter

## calmcore




