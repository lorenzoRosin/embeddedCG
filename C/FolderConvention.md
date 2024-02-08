# FOLDER CONVENTION - LIBRARY
When writing a library the folder structure will be as follow:
- README.md <br>
- LICENSE <br>
- List of folders named after the programming language used<br><br>

Inside the folder called after the programming language used the struct will be:
- 0_Docs ----> Folder containings all the documentation stuff<br>
- 1_Ws ------> Folder Containing the used works space<br>
- 2_ExtLib  ---> Folder containings all the used external libs<br>
- 3_Src ------> Folder containings the source code<br>
- 4_Test -----> Folder containings all the related test stuff<br>
- 5_Tools ----> Folder containings software tools stuff <br>
- 6_Releases -> Folder containings eventual binary releases <br><br>

Inside the 1_Ws folder we will put the works space related data inside another folder named after the used IDE.<br>
Inside the 2_ExtLib folder we will put the external library related data inside another folder named after the used library.<br>
Inside the 3_Src folder we will put the source code related data inside another folder named after modules names.<br><br>
4_Test folder will have the following structure:
- 0_Docs ----> Folder containings all the documentation stuff related to the test phase<br>
- 1_Ws ------> Folder Containing the used works space for the test<br>
- 2_ExtLib  ---> Folder containings all the used external libs for testing<br>
- 3_Src ------> Folder containings the source code of the test<br>

0_Docs, 1_Ws, 2_ExtLib and 3_Src folder inside 4_Test mantains the same structure already described for the folder inside the main project


<br>

# FOLDER CONVENTION - PROJECT
When writing a project the folder structure will be as follow:
- README.md <br>
- LICENSE <br>

- 0_Docs ----> Folder containings all the documentation stuff<br>
- 1_Ws ------> Folder Containing the used works space<br>
- 2_ExtLib  ---> Folder containings all the used external libs<br>
- 3_Src ------> Folder containings the source code<br>
- 4_Test -----> Folder containings all the related test stuff<br><br>

Inside the 1_Ws folder we will put the works space related data inside another folder named after the used IDE.<br>
Inside the 2_ExtLib folder we will put the external library related data inside another folder named after the used library.<br>
Inside the 3_Src folder we will put the source code related data inside another folder named after modules names.<br><br>
4_Test folder will have the following structure:
- 0_Docs ----> Folder containings all the documentation stuff related to the test phase<br>
- 1_Ws ------> Folder Containing the used works space for the test<br>
- 2_ExtLib  ---> Folder containings all the used external libs for testing<br>
- 3_Src ------> Folder containings the source code of the test<br>

0_Docs, 1_Ws, 2_ExtLib and 3_Src folder inside 4_Test mantains the same structure already described for the folder inside the main project


<br>

# FOLDER CONVENTION - GENERAL NOTES
Every structure discussed above must be mantained even if a folder is empty. In order to publish on github an empty folder we must insert a file called ".gitkeep"
