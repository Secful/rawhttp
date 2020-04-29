{{ define title "RawHTTP" }}
{{ define moduleName "Get Started" }}
{{ define path baseURL + "/docs/get-started.html" }}
{{ include /processed/fragments/_header.html }}
{{ include /processed/fragments/_nav.html }}

## Add a dependency on RawHTTP

### Maven

```xml
<dependency>
    <groupId>com.athaydes.rawhttp</groupId>
    <artifactId>rawhttp-core</artifactId>
    <version>2.3.0</version>
</dependency>
```

### Gradle

```groovy
dependency 'com.athaydes.rawhttp:rawhttp-core:2.3.0'
```

### Download the jar with curl

```
curl https://jcenter.bintray.com/com/athaydes/rawhttp/rawhttp-core/2.3.0/rawhttp-core-2.3.0.jar -o rawhttp.jar
```

<hr>

{{ include /processed/fragments/_footer.html }}