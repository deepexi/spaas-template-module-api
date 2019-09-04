```xml
mvn archetype:generate  \
  -DarchetypeGroupId=com.github.deepexi     \
  -DarchetypeArtifactId=optimus-archetype-springcloud  \
  -DarchetypeVersion=3.1.2     \
  -DgroupId=com.deepexi      \
  -DartifactId=deepexi-module    \
  -DarchetypeCatalog=local   \
  -DappName=deepexiModule  \
  -Dversion=1.0-SNAPSHOT  \
  -Dpackage=com.deepexi.deepexiModule \
  -DinteractiveMode=false



mvn archetype:generate \
 -DarchetypeGroupId=com.deepexi     \
 -DarchetypeArtifactId=parent-module  \
 -DarchetypeVersion=1.0.0 \
 -DgroupId=com.deepexi \
 -DartifactId=deepexi-module-demo \
 -DinteractiveMode=false


```


