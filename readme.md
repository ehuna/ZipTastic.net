Ziptastic.net Class Library
===================

Welcome to the ZipTastic .net Class Library. 

**Version 1.1 to 1.2 Upgrade Alert**  
If you were using version 1.1 and upgrade to this version there are breaking changes that have occurred. 

    _state is no longer available. 
    state is now the officially supported option.


**Installation**   
You can now install ZipTastic.net using NuGet. Use the search box to search for ZipTastic.net or use the code below:   

    PM> Install-Package Ziptastic.net


**Simple usage**   

    Imports ZipTastic
    Dim myZips As New ZipTastic.getZipInfo
    Dim myZipCodeData As iZip = myZips.getZipData("06281", "US")
    MsgBox(myZipCodeData.City & " : " & myZipCodeData.State)

For more information see our article on Stupid Code Tricks
http://www.stupidcodetricks.com/net-framework/intermediate/ziptastic-net-class-library/

License 
===================

This work is licensed under a Creative Commons Attribution 3.0 Unported License.
http://creativecommons.org/licenses/by/3.0/