# FOLDER CONVENTION - LIBRARY
When writing a library the folder structure will be as follow:
- README.md <br>
- LICENSE <br>
- List of folders named after the programming language used<br><br>

Inside the folder, called after the programming language in use, the struct will be:
- 0_Docs ------> Folder containings all the documentation stuff<br>
- 1_Ws --------> Folder containing the used works space<br>
- 2_Src --------> Folder containings the source code<br>
- 3_ExtLib  -----> Folder containings all the used external libs<br>
- 4_Test -------> Folder containings all the related test stuff<br>
- 5_Tools ------> Folder containings software tools stuff <br>
- 6_Releases --> Folder containings eventual binary releases <br><br>

Inside the 1_Ws folder we will put the works space related data inside another folder named after the used IDE or compiler.<br>
Inside the 2_Src folder we will put the source code related data inside another folder named after modules names.<br>
Inside the 3_ExtLib folder we will put the external library related data inside another folder named after the used library.<br>
Inside the 5_Tools folder we will put all the software tools related data inside another folder named after the tools name.<br>
Inside the 6_Releases folder we will put all the bynary releases, if any, in a folder named as the software release.
Bynary software releases will contain a release note also.<br><br>


4_Test folder will have the following structure:
- 0_Docs ------> Folder containings all the documentation stuff related to the test phase<br>
- 1_Ws --------> Folder Containing the used works space for the test<br>
- 2_Src --------> Folder containings the source code of the test<br>
- 3_ExtLib  -----> Folder containings all the used external libs for testing<br>
- 4_Tools ------> Folder containings software tools stuff used for testing <br>


0_Docs, 1_Ws, 2_Src, 3_ExtLib and 4_Tools folder inside 4_Test mantains the same structure already described for the folder inside the main project


<br>

# FOLDER CONVENTION - PROJECT
When writing a project the folder structure will be as follow:
- README.md <br>
- LICENSE <br>
- 0_Docs ------> Folder containings all the documentation stuff<br>
- 1_Ws --------> Folder containing the used works space<br>
- 2_Src --------> Folder containings the source code<br>
- 3_ExtLib  -----> Folder containings all the used external libs<br>
- 4_Test -------> Folder containings all the related test stuff<br>
- 5_Tools ------> Folder containings software tools stuff <br>
- 6_Releases --> Folder containings eventual binary releases <br><br>

Inside the 1_Ws folder we will put the works space related data inside another folder named after the used IDE or compiler.<br>
Inside the 2_Src folder we will put the source code related data inside another folder named after modules names.<br>
Inside the 3_ExtLib folder we will put the external library related data inside another folder named after the used library.<br>
Inside the 5_Tools folder we will put all the software tools related data inside another folder named after the tools name.<br>
Inside the 6_Releases folder we will put all the bynary releases, if any, in a folder named as the software release.
Bynary software releases will contain a release note also.<br><br>


4_Test folder will have the following structure:
- 0_Docs ------> Folder containings all the documentation stuff related to the test phase<br>
- 1_Ws --------> Folder Containing the used works space for the test<br>
- 2_Src --------> Folder containings the source code of the test<br>
- 3_ExtLib  -----> Folder containings all the used external libs for testing<br>
- 4_Tools ------> Folder containings software tools stuff used for testing <br>


0_Docs, 1_Ws, 2_Src, 3_ExtLib and 4_Tools folder inside 4_Test mantains the same structure already described for the folder inside the main project


<br>

# FOLDER CONVENTION - GENERAL NOTES
Every structure discussed above must be mantained even if a folder is empty. In order to publish on github an empty folder we must insert a file called ".gitkeep"
