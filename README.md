
* Horde3D http://www.horde3d.org
* Language bindings http://horde3d.org/wiki/index.php5?title=Language_Bindings
* Basic bindings for Java https://bitbucket.org/fk/horde3d-java

## Building Horde3D Mac

For building on OS X use source control versions NOT download.

I'm not sure yet which is best:

* git clone git@github.com:horde3d/Horde3D.git
* svn co svn://svn.code.sf.net/p/horde3d/code/trunk horde3d
 
Use cmake and Xcode generator.

```
cmake -G Xcode
```

Then build and compile in Xcode (Sorry).
