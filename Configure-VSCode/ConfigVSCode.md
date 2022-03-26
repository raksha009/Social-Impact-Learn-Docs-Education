<!-- Output copied to clipboard! -->

<!-----


----->






# How to configure C/C++ in VS  Code

Properly configuring a C/C++ Compiler is really important for VS Code as if the compilers are not pre installed then it would be hard to run the source code. In order to avoid that let us 1st configure the compiler.


## Download Mingw



* Go to [https://sourceforge.net/projects/mingw/](https://sourceforge.net/projects/mingw/) and download the file.






![alt_text](/Configure-VSCode/images/p1.png "image_tooltip")




*  Now install the downloaded setup. After successfully installing a pop up will show as shown 




![alt_text](/Configure-VSCode/images/p2.gif "image_tooltip")


Now install mingw32-base and mingw32-gcc g++ package. Now go to the Installation tab and click Apply Changes.

![alt_text](/Configure-VSCode/images/p4.png "image_tooltip")

* Now go to your C Drive (Where the OS is installed) and find the MinGW Folder. All the downloaded packages will be saved under the bin. Now copy the bin path for eg (C:\MinGW\bin)
* Now go to the settings click on advanced system settings.Click on EnvironmentVariables.




![alt_text](/Configure-VSCode/images/p3.png "image_tooltip")

* Now select the path then click on edit and then click new then paste the copied path of the bin folder for eg ( C:\MinGW\bin ) and then click on OK
  
![alt_text](/Configure-VSCode/images/p5.gif "image_tooltip")

* If you type the following in your command prompt you can see that C compiler is properly configured 
  
  
![alt_text](/Configure-VSCode/images/p6.gif "image_tooltip")

    

