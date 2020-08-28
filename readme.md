# Kafka Learn

## Kafka Theory

### Topics, Partitions and offsets

- `Topic`: 
    - A particular stream of data
    - as Many topics as you want
    - identified by its name
    - `Similar to tables in databases`
    - Split in `partitions`
    - Default is 6 partitions, but can be changed
- `Partition`:
    - Part of the Topic
`Messages`:
    - You can have as much as you want
- `Offsets`:
    - Incremental Id of a message

### Brokers and Topics

A cluster is composed of multiple brokers

