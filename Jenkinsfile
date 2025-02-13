Started by user sagar chouhan
[Pipeline] Start of Pipeline
[Pipeline] node
Running on Jenkins in /var/lib/jenkins/workspace/pipeline-08-02
[Pipeline] {
[Pipeline] stage
[Pipeline] { (git scm checkout)
[Pipeline] git
The recommended git tool is: NONE
No credentials specified
Cloning the remote Git repository
Cloning repository https://github.com/kumargaurav039/maven-project.git
 > /usr/bin/git init /var/lib/jenkins/workspace/pipeline-08-02 # timeout=10
Fetching upstream changes from https://github.com/kumargaurav039/maven-project.git
 > /usr/bin/git --version # timeout=10
 > git --version # 'git version 2.47.1'
 > /usr/bin/git fetch --tags --force --progress -- https://github.com/kumargaurav039/maven-project.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > /usr/bin/git config remote.origin.url https://github.com/kumargaurav039/maven-project.git # timeout=10
 > /usr/bin/git config --add remote.origin.fetch +refs/heads/*:refs/remotes/origin/* # timeout=10
Avoid second fetch
 > /usr/bin/git rev-parse refs/remotes/origin/master^{commit} # timeout=10
Checking out Revision 9ce3ecd4a3b5a7dbc61186f97d8e9e95360a8e51 (refs/remotes/origin/master)
 > /usr/bin/git config core.sparsecheckout # timeout=10
 > /usr/bin/git checkout -f 9ce3ecd4a3b5a7dbc61186f97d8e9e95360a8e51 # timeout=10
 > /usr/bin/git branch -a -v --no-abbrev # timeout=10
 > /usr/bin/git checkout -b master 9ce3ecd4a3b5a7dbc61186f97d8e9e95360a8e51 # timeout=10
Commit message: "Update index.jsp"
First time build. Skipping changelog.
[Pipeline] }
[Pipeline] // stage
[Pipeline] stage
[Pipeline] { (build)
[Pipeline] withMaven
[withMaven] Options: []
[withMaven] Available options: 
[withMaven] using JDK installation JAVA_HOME
[withMaven] using Maven installation 'MVN_HOME'
[withMaven] found Maven version: Apache Maven 3.2.5 (12a6b3acb947671f09b81f49094c53f426d8cea1; 2014-12-14T17:29:23+00:00)
[withMaven] WARNING: You are running an old version of Maven (3.2.5), you should update to at least 3.8.x
[Pipeline] {
[Pipeline] sh
+ mvn validate
----- withMaven Wrapper script -----
Picked up JAVA_TOOL_OPTIONS: -Dmaven.ext.class.path="/var/lib/jenkins/workspace/pipeline-08-02@tmp/withMaven504bcb38/pipeline-maven-spy.jar" -Dorg.jenkinsci.plugins.pipeline.maven.reportsFolder="/var/lib/jenkins/workspace/pipeline-08-02@tmp/withMaven504bcb38" 
Apache Maven 3.2.5 (12a6b3acb947671f09b81f49094c53f426d8cea1; 2014-12-14T17:29:23+00:00)
Maven home: /usr/share/apache-maven
Java version: 17.0.14, vendor: Amazon.com Inc.
Java home: /usr/lib/jvm/java-17-amazon-corretto.x86_64
Default locale: en, platform encoding: UTF-8
OS name: "linux", version: "6.1.127-135.201.amzn2023.x86_64", arch: "amd64", family: "unix"
[INFO] [jenkins-event-spy] Generate /var/lib/jenkins/workspace/pipeline-08-02@tmp/withMaven504bcb38/maven-spy-20250208-072435-3958832671057699208468.log.tmp ...
[INFO] Scanning for projects...
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO] 
[INFO] Maven Project
[INFO] Server
[INFO] Webapp
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Project 1.0-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] Downloading: https://repo.maven.apache.org/maven2/org/jacoco/jacoco-maven-plugin/0.8.2/jacoco-maven-plugin-0.8.2.pom
[INFO] Downloaded: https://repo.maven.apache.org/maven2/org/jacoco/jacoco-maven-plugin/0.8.2/jacoco-maven-plugin-0.8.2.pom (5 KB at 9.8 KB/sec)
[INFO] Downloading: https://repo.maven.apache.org/maven2/org/jacoco/org.jacoco.build/0.8.2/org.jacoco.build-0.8.2.pom
[INFO] Downloaded: https://repo.maven.apache.org/maven2/org/jacoco/org.jacoco.build/0.8.2/org.jacoco.build-0.8.2.pom (39 KB at 633.3 KB/sec)
[INFO] Downloading: https://repo.maven.apache.org/maven2/org/jacoco/jacoco-maven-plugin/0.8.2/jacoco-maven-plugin-0.8.2.jar
[INFO] Downloaded: https://repo.maven.apache.org/maven2/org/jacoco/jacoco-maven-plugin/0.8.2/jacoco-maven-plugin-0.8.2.jar (53 KB at 1590.4 KB/sec)
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building Server 1.0-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building Webapp 1.0-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO] 
[INFO] Maven Project ...................................... SUCCESS [  1.352 s]
[INFO] Server ............................................. SUCCESS [  0.001 s]
[INFO] Webapp ............................................. SUCCESS [  0.001 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 1.664 s
[INFO] Finished at: 2025-02-08T07:24:37+00:00
[INFO] Final Memory: 9M/21M
[INFO] ------------------------------------------------------------------------
[INFO] [jenkins-event-spy] Generated /var/lib/jenkins/workspace/pipeline-08-02@tmp/withMaven504bcb38/maven-spy-20250208-072435-3958832671057699208468.log
[Pipeline] }
[withMaven] artifactsPublisher - Archive artifact pom.xml under com/example/maven-project/maven-project/1.0-SNAPSHOT/maven-project-1.0-SNAPSHOT.pom
[withMaven] artifactsPublisher - Archive artifact server/pom.xml under com/example/maven-project/server/1.0-SNAPSHOT/server-1.0-SNAPSHOT.pom
[withMaven] artifactsPublisher - Archive artifact webapp/pom.xml under com/example/maven-project/webapp/1.0-SNAPSHOT/webapp-1.0-SNAPSHOT.pom
[withMaven] Jenkins FindBugs Plugin not found, don't display org.codehaus.mojo:findbugs-maven-plugin:findbugs results in pipeline screen.
[withMaven] jgivenPublisher - Jenkins JGiven Plugin not found, do not archive jgiven reports.
[withMaven] Jenkins Task Scanner Plugin not found, don't display results of source code scanning for 'TODO' and 'FIXME' in pipeline screen.
[withMaven] Publishers: Pipeline Graph Publisher: 13 ms, Generated Artifacts Publisher: 51 ms, Findbugs Publisher: 1 ms, Maven Linker Publisher: 7 ms
[Pipeline] // withMaven
[Pipeline] }
[Pipeline] // stage
[Pipeline] }
[Pipeline] // node
[Pipeline] End of Pipeline
Finished: SUCCESS
