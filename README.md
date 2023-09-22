# Parquet2.jl Test Files
Local parquet files to represent standard use-cases of large datasets I might need to work with in Julia.

*Key Concept: eliminate the need for an intermediate dataset read/filter operation before working in Julia. I'd like to be able to do even large-scale processing in Julia rather than break into a new context with Spark or other tools.*

## PATITIONED FILES WRITTEN BY
>single string (or date) partition file structure

spark scala
duckdb
redshift unload
trino external table

## DATA TYPES
    boolean
    date
    timestamp
    float/double
    int32
    int64
    string
