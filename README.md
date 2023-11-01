## Description

Made a maven repo that contains dependencies that I could only find on http sites
Now they are on a https site and can be used on machines that block non-secure sites.
I may be adding to this in the future depending on my needs.

If anyone else wants to use it just add the relevant lines below to your pom.
### Repository
```
<repository>
  <id>GitHub</id>
	<name>GitHub Repo</name>
	<url>https://raw.githubusercontent.com/zjack8/maven-repo/main/</url>
</repository>
```
### Dependencies
Pick and choose which are relevant to your project. There are also more in this repo but these are specifically only on http.
#### Kabeja
```
<dependency>
	<groupId>org.kabeja</groupId>
	<artifactId>kabeja</artifactId>
	<version>0.4</version>
</dependency>
```

#### Aspose Cad
```
<dependency>
	<groupId>com.aspose</groupId>
	<artifactId>aspose-cad</artifactId>
	<version>22.3</version>
</dependency>
```

#### Aspose Words
```
<dependency>
	<groupId>com.aspose</groupId>
	<artifactId>aspose-words</artifactId>
	<version>21.11</version>
	<type>pom</type>
</dependency>
```

#### Aspose Cells
```
<dependency>
	<groupId>com.aspose</groupId>
	<artifactId>aspose-cells</artifactId>
	<version>23.9</version>
</dependency>
```
