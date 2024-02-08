# FILE CONVENTION - LIBRARY
When writing a library the naming convention for file will be as follow:
- libraryname_MODULENAME <br>


where libraryname is the name of the library (lower/upper caps), and where MODULENAME is the name of the module, all in upper caps.<br>
If the file that we are using is a private file of the module the name will be as follow:
- libraryname_MODULENAME_PRV <br><br>

File must be store in a folder called: MODULENAME, and inside this folder we must find other two folder: Inc and Src<br>

# FILE CONVENTION - PROJECT
When writing a project the naming convention for file will be as follow:
- projectname_ModuleName <br>


where projectname is the name of the project (lower/upper caps), and where ModuleName is the name of the module,with the first letter in capital letter and the other one in lower case, exept for the letter that separate multi word<br>
If the file that we are using is a private file of the module the name will be as follow:
- projectname_ModuleName_prv <br><br>

File must be store in a folder called: ModuleName, and inside this folder we must find other two folder: Inc and Src<br>


# FILE CONVENTION - HEADER AND COMMENTS
Every file must have the following header:<br>

<code>
<pre>
/**
  * @file       filename.fileextension
  *
  * @brief      file description
  *
  * @author     Autor name
  *
  * @copyright  MIT License, Copyright (c) 2024 Autor name
  *
  **********************************************************************************************************************/
</pre>
</code>

Every function must have the following header:<br>

<code>
<pre>
/**
  * @brief       Function description
  *
  * @param[in/out]   paramname      - param description
  *
  * @return      return type     - return description
  */
</pre>
</code>

Include must be introduced by this header <br>

<code>
<pre>
/***********************************************************************************************************************
 *      INCLUDES
 **********************************************************************************************************************/
</pre>
</code>

Typedef must be introduced by this header <br>

<code>
<pre>
/***********************************************************************************************************************
 *      TYPEDEFS
 **********************************************************************************************************************/
</pre>
</code>

Typedef must be introduced by this header <br>

<code>
<pre>
/***********************************************************************************************************************
 * GLOBAL PROTOTYPES
 **********************************************************************************************************************/
</pre>
</code>

Typedef must be introduced by this header <br>

<code>
<pre>
/***********************************************************************************************************************
 *  PRIVATE STATIC FUNCTION DECLARATION
 **********************************************************************************************************************/
</pre>
</code>

Typedef must be introduced by this header <br>

<code>
<pre>
/***********************************************************************************************************************
 *   GLOBAL FUNCTIONS
 **********************************************************************************************************************/
</pre>
</code>

# FILE CONVENTION - FILE FORMATTING
Every file must:
-Use 4 space instead of tabs
-Do not exceeed 120 lines of code or comments

<br>