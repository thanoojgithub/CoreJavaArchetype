# CoreJavaArchetype
creating custom Core Java Archetype



steps :

mvn archetype:generate -DgroupId=com.corejava -DartifactId=CoreJavaArchetype -Dpackage=com.corejava -Dname="CoreJavaArchetype" -Ddescription="Core Java Archetype" -Dversion="1.0" -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

make sure, project structure. for more details : project_structure.png

and then,

mvn -o archetype:generate -DarchetypeGroupId=com.corejava -DarchetypeArtifactId=CoreJavaArchetype -DarchetypeVersion=1.0 -DgroupId=com.corejava -DartifactId=CoreJavaOne -Dpackage=com.corejava -Ddescription="Core Java One" -Dversion="1.0"




http://maven.apache.org/guides/mini/guide-creating-archetypes.html

https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html



