I made this archetype to make it easier to start future Java projects with maven.
To install: mvn install
To generate a project from this archetype: 
    1. mvn archetype:generate -DarchetypeGroupId=dye.charlotte -DarchetypeArtifactId=standardArchetype -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=*specify_group_id* -DartifactId=*specify_artifact_id*
    2. Open POM and update names
    3. Build with mvn install
    4. Run with java -jar target\project-name-1.0-SNAPSHOT.jar
