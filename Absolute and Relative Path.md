# Absolute and Ralative Pathnames in UNIX


**What is absolute path-name?**

**Ans:**

*An absolute path is defined as the specifying the location of a file or  directory from the root   directory(/).*

 **To write an absolute path-name:**
 * Start at the root directory (/) and work down.
 * Write a slash (/) after every directory name (last one is optional)
 
 Ex:/home/ec2-user/abc.txt


**What is relative path-name?**

**Ans:**

*Relative path is defined as the path related to the present working directly(pwd). It starts at your    current directory and never starts with a /*

*UNIX offers a shortcut in the relative pathname– that uses either the current or parent directory as    reference and specifies the path relative to it. A relative path-name uses one of these cryptic    symbols:*

   * .(a single dot) - this represents the current directory.
   * ..(two dots) - this represents the parent directory. 
 
   Ex:cd ../..



