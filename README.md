# Java-BackEnd 환경설정

create backEnd file

https://www.eclipse.org/downloads/packages/
Eclipse IDE for Enterprise Java and Web Developers_windows x86_64 download

https://tomcat.apache.org/download-90.cgi
Core 64-bit Windows zip download


시스템 환경 변수 편집 > 환경 변수 > 시스템 변수 >
새로 만들기
CATALINA_HOME | "D:\backEnd\apache-tomcat-9.0.80" 맨 위로 이동
JAVA_HOME | "C:\Program Files\Java\jdk-17"

새로 만들기
Path | "C:\Program Files\Java\jdk-17\bin", "D:\backEnd\apache-tomcat-9.0.80\bin"
위로이동

app > Window > Preferences > Search Files > Web >
CSS Files | HTML Files | JSP Files > Encoding | ISO 10646/Unicode(UTF-8)

File > New > Dynamic Web Project > web Module > check Generate web.xml deployment descriptor
src > main > webapp > New > create file

Servers > New > Server > Apache > Check Tomcat v9.0 > Add folder > Click Finish

cmd > startup 

# bootstrap (CSS)

https://getbootstrap.com/docs/5.1/getting-started/download/ > Getting started > Download > Compiled CSS and JS Download 

backEnd > webapp > create css > 
bootstrap file name "bootstrap-5.1.3-dist" > css > bootstrap.min.css > Add backEnd/css file 

# backEnd file setting
Java Resources folder > Craete Servlet > Java package, Class name > next > Add URL Mappings > Pattern file name "/*" > doGet, doPost >
"protected void doGet" in response.getWriter()... 주석

# JSP mySQL
mysql 8.0.34버전 설치, mysql workbench 8.0.34버전 설치, mariadb-10.3.14 버전 설치, mysql-connector-j-8.0.32 버전 설치
mysql-connector-j-8.0.32 압축 풀기 -> "mysql-connector-j-8.0.32.jar", "Java\jdk-17\lib"경로에 넣어주기





