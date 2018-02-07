# jmorphy2-lucene

Maven version of [jmorphy2](https://github.com/anti-social/jmorphy2) v0.2.0 (Java port of the [pymorphy2](https://pymorphy2.readthedocs.io/))

### Includes
- dawg
- jmorphy2-core
- jmorphy2-dicts-ru (from pymorphy2-dicts-ru/2.4.404381.4453942)
- jmorphy2-dicts-uk (from pymorphy2-dicts-uk/2.4.1.1.1460299261)
- jmorphy2-nlp
- jmorphy2-lucene

### Not includes
- Elasticsearch plugin

### Usage

Repository
```
<repositories>
    <repository>
        <id>drxaos</id>
        <name>mvn-repo</name>
        <url>https://github.com/drxaos/mvn-repo/raw/master/</url>
    </repository>
</repositories>
```

Dependency
```
<dependencies>
    <dependency>
        <groupId>company.evo</groupId>
        <artifactId>jmorphy2-lucene</artifactId>
        <version>0.2.0</version>
    </dependency>
</dependencies>
```

