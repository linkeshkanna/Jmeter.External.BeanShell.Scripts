# Jmeter.External.BeanShell.Scripts
Sample Jmeter BeanShell Scripts to Process some 'n' Number of TextFiles into your Requests

If you have the below requirement, the following script will help you.

1. I have some 'n' number of text files under two directories - 'DirectoryOne and DirectoryTwo'.
2. For First Request I have to Process the 'n' number of files under 'DirectoryOne' and have to pass it as a Post Body Request
   for ThreadGroup1 using a ForEach Controller.
3. For Second Request, I have to Process the 'n' number of files under 'DirectoryTwo' and have to pass it as a Post Body Request
   for ThreadGroup2 using a ForEach Controller.
4. Also I have illustrated a way to use relative path in Jmeter by pointing to the root directory where the test plan file exists.
