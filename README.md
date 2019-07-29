# presto-parcel
presto for Cloudera Manager parcel

# Build

```
mvn -Djdk.tar.gz.path=/your/path/to/jdk.tar.gz package
```

- By default, use `prestosql/presto` repository ( https://github.com/prestosql/presto )
- If you want to use `prestodb/presto` repository ( https://github.com/prestodb/presto ), configure properties for pom
  - e.g.) use `prestodb/presto` version 0.218:
```
mvn -Dpresto.url.base="https://repo1.maven.org/maven2/com/facebook/presto" -Dpresto.version=0.218 -Djdk.tar.gz.path=/your/path/to/jdk.tar.gz package
```

# Deploy

https://github.com/cloudera/cm_ext/wiki/The-parcel-repository-format#structure-of-a-parcel-repository

# About Presto

https://prestodb.io/

# About Cloudera Manager

http://www.cloudera.com/content/www/en-us/products/cloudera-manager.html

# About parcel

https://github.com/cloudera/cm_ext/wiki/Parcels%3A-What-and-Why%3F
