## Installations / Reference Material :

[JDK](https://www.oracle.com/java/technologies/downloads/)

[JRE](https://download.cnet.com/Java-Runtime-Environment-JRE/3000-2213_4-10009607.html)

[Cloudsim](https://github.com/Cloudslab/cloudsim/releases)

[Eclipse](https://www.eclipse.org/downloads/)


### Steps :
1. Install any of the IDE for running JAVA applications (eclipse recommended)
2. Install JDK and JRE for the same
3. Add the jdk\bin path to the environment variables
Open environment variables window, add the following to the path variable
```
Do include your bin path wherever you have installed JDK
Mine is as  following :
> C:\Program Files\Java\jdk-14.0.1\bin
```
4. Open eclipse in your confined workspace 
5. Click on new and open a new **JAVA Project**, give it a name
6. Create a package inside he src folder.
7. Now right click on the project and choose **configure build path**.
8. Click on the libraries section and add external jars
9. Extract the Cloudsim.tar file you downloaded
10. Now import the jar files in that Cloudsim.tar into the external jars.
11. Do remeber to change the name of the package in all the source files.
12. Now right click on the project and run the project as **JAVA Application**.
13. Select the SJF_Scheduler.java file present in the list.

### Done..!!
