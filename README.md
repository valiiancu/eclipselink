EclipseLink Project
========================================

The EclipseLink project's goal is to provide a complete persistence framework that is both comprehensive and universal. It will run in any Java environment and read and write objects to virtually any type of data source, including relational databases, XML, JSON, or EIS systems. EclipseLink will focus on providing leading edge support, including advanced feature extensions, for the dominant persistence standards for each target data source; Java Persistence API (JPA) for relational databases, Java API for XML Binding (JAXB) for XML, Java Connector Architecture (JCA) for EIS and other types of legacy systems, and Service Data Objects (SDO).


http://eclipse.org/eclipselink



Building
========================================

Tools
* c:\tools\apache-ant-1.9.16 
* c:\tools\apache-maven-3.8.6 
* c:\Program Files\Eclipse Adoptium\jdk-8.0.352.8-hotspot

Run these in the eclipselink folder (change date & hash)
```
SET M2_HOME=c:\tools\apache-maven-3.8.6
SET JAVA_HOME=c:\Program Files\Eclipse Adoptium\jdk-8.0.352.8-hotspot
c:\tools\apache-ant-1.9.16\bin\ant -f antbuild.xml -Dtype=r -Dversion=1.6.6mdsy -Ddate=20221212 -Dhash=77f2de35 clean,build-eclipselink-jar
```
