# mwdumper
mediawiki parser

how to use
1. mvn package
2. run the following command:
java -jar mwdumper-1.16.jar --output=file:sql14file --format=mysql:1.4 enwiki-20160204-pages-meta-current.xml.bz2 > 14file

file:sql14file means the sql command file
14file means the raw file content which is used in terarkdb
