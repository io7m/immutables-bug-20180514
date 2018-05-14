```
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building immutables-bug-20180514 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ immutables-bug-20180514 ---
[INFO] Deleting /home/rm/git/com.github/io7m/immutables-bug-20180514/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ immutables-bug-20180514 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ immutables-bug-20180514 ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 2 source files to /home/rm/git/com.github/io7m/immutables-bug-20180514/target/classes
[INFO] -------------------------------------------------------------
[ERROR] COMPILATION ERROR : 
[INFO] -------------------------------------------------------------
[ERROR] /home/rm/git/com.github/io7m/immutables-bug-20180514/target/generated-sources/annotations/com/io7m/bugs/ImmutableThingType.java:[4,24] package javax.annotation.processing is not visible
  (package javax.annotation.processing is declared in module java.base, which does not export it)
[INFO] 1 error
[INFO] -------------------------------------------------------------
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 2.214 s
[INFO] Finished at: 2018-05-14T10:08:57+01:00
[INFO] Final Memory: 15M/54M
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile (default-compile) on project immutables-bug-20180514: Compilation failure
[ERROR] /home/rm/git/com.github/io7m/immutables-bug-20180514/target/generated-sources/annotations/com/io7m/bugs/ImmutableThingType.java:[4,24] package javax.annotation.processing is not visible
[ERROR]   (package javax.annotation.processing is declared in module java.base, which does not export it)
[ERROR] 
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException
```
