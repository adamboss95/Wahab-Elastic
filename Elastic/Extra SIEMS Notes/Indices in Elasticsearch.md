# Indices in Kibana and Elasticsearch

In Kibana and Elasticsearch, the term **"indices"** is used to *refer to logical namespaces that hold collections of documents*. Each document is a collection of fields, similar to rows in a relational database table. Indices are the largest unit of data in Elasticsearch and serve as a way to organize and store data efficiently.

## Key Points About Indices in Kibana

### Indices

 **Definition**:
 An index in Elasticsearch is a logical namespace that holds a collection of documents. Each document is a collection of fields, similar to rows in a relational database table.

- **What**: A place where data is stored in Elasticsearch.
    
- **Purpose**: Holds documents with similar characteristics.
    
### Index Patterns

 **Definiton**: In Kibana, an **index pattern** is used to define which Elasticsearch indices or data streams you want to explore. It can include wildcards to match multiple indices, making it easier to analyze large datasets across multiple sources.

- **What**: A way to select which indices you want to explore in Kibana.
    
- **Purpose**: Helps access multiple indices at once using wildcards.

### Data Views

**Definition**: In newer versions of Kibana, **data views** have replaced index patterns for accessing Elasticsearch data. A data view can point to one or more indices, data streams, or index aliases.

- **What**: A newer way to access data in Kibana, replacing index patterns.
    
- **Purpose**: More flexible than index patterns; can point to multiple indices or data streams.

### Simple Analogy

- **Indices** are like folders where you store files.
    
- **Index Patterns/Data Views** are like shortcuts that help you find and explore files across multiple folders.

### Key Point

- **Indices** store data.
    
- `**Index Patterns/Data Views** help you access and explore this data in Kibana.