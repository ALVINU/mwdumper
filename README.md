# mwdumper
mediawiki parser

how to use

1. mvn package

2. the jar file(mwdumper-1.16.jar) is in ~/target, and run the following command:

java -jar mwdumper-1.16.jar --format=mysql:1.4 enwiki-20160204-pages-meta-current.xml.bz2 > 14file

14file which you can specify means the raw file content which is used in terarkdb
