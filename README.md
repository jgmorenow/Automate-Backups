<h1>Automate Backups with Python Script</h1>


<h2>Description</h2>
<b>In this project, I will demonstrate how I automate backup with a Python script. 
File backups are critical for preserving data in local storage. I will use the shutil, os, and sys modules. 
Shutil module is used to copy data from one file to another. Os and sys modules are used to get the directory path and so on. 

</b>
<br />
<br />
<h2>Implementation:</h2>

- <b> Step 1:</b>  <b>Importing shutil, os, and sys modules</b>

<br />
<br />

<p align="center">
<img src="https://i.imgur.com/Q3sOpNd.png" height="25%" width="75%" />
</p>

- <b>Step 2:</b> <b>Now we need today’s date using the datetime module</b>

<p align="center">
<img src="https://i.imgur.com/BsIIwER.png" height="25%" width="75%" />
</p>

- <b>Step 3:</b> <b>If we have the specific path to the source file, we can use the line below to concatenate the path to the source file with the name of the source file.
</b>

<p align="center">
<img src="https://i.imgur.com/59FmTLF.png" height="50%" width="75%" />
</p>

- <b>However, if we don’t, and our file is stored in the same directory as our current Python script, we can use the os module to determine the current path of the file and create the source directory by combining the path provided by the os module with the source file name. 
</b>

<p align="center">
<img src="https://i.imgur.com/r7RHFHm.png" height="50%" width="75%" />
</p>

- <b>Step 4:</b> <b>If we do not specify the source file name, we must return a file does not exist error.
</b>

<p align="center">
<img src="https://i.imgur.com/bsBPj1q.png" height="50%" width="75%" />
</p>
<p align="center">
<img src="https://i.imgur.com/jMNW209.png" height="50%" width="75%" />
</p>

- <b>Step 5:</b> <b>Now, we can use the following cases to test the conditions. 

If we provide all the necessary inputs, such as source file name, source file path, destination file name, and destination file path. 

</b>

<p align="center">
<img src="https://i.imgur.com/5o4b2Me.png" height="50%" width="75%" />
     
</p>

<b>If the destination file name is None, which indicates we did not specify a destination file name, we will use the following condition. 
</b>

<p align="center">
<img src="https://i.imgur.com/S0dkCd1.png" height="50%" width="75%" />
     
</p>

<b>If we enter an empty string with one or more spaces. 
</b>

<p align="center">
<img src="https://i.imgur.com/RyWp003.png" height="50%" width="75%" />
     
</p>


