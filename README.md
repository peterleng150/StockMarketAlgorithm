# StockMarketAlgorithmApp
The information system chosen for the project was a stock investment management website providing live prices, historical data, news articles, etc and also basic analysis and recommendations using data mining techniques. 1. Crawling and parsing Yahoo-Finance, Reuters and Twitter data (Java, twitter4j). 2. Web Interface using J2EE and Struts-2 framework. jQuery (highstocks lib) for showing technical charts. 3. Database integration, data cleaning, feature selection on the collected data and applying linear regression and classification algorithms : SVM, Naive Bayes to produce detailed analysis and recommendations.

# How to Build

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Crawler.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
