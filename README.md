https://blog.csdn.net/mouday/article/details/107718651

```sh
mvn deploy:deploy-file 
-Dmaven.test.skip=true 
-Dfile= D:\project\ninux-github-facility\target\ninux-github-facility-1.0.0.jar 
-DgroupId=com.example 
-DartifactId=ninux-github-facility 
-Dversion=1.0.0 
-Dpackaging=jar 
-DrepositoryId=github -Durl=https://github.com/ninuxGithub/ninux-github-facility


```