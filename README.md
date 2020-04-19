### Requirements:

- java8 +
- Apache Thrift - https://thrift.apache.org - ```scoop install thrift```

#### Both src/main/java and gen-java directories should be set as source directories in Intellij

```
thrift --gen java calculator.thrift
```