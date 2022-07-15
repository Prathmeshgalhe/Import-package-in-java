# Import-package-in-java
(Program to create package) 
public class gfg {

	public void show()
	{
		System.out.println("Hello geeks!! How are you?");
	}

	public static void main(String args[])
	{
		gfg obj = new gfg();
		obj.show();
	}
}

(Program to import package) 

import example.gfg;

public class GFG {
	public static void main(String args[])
	{
		gfg obj = new gfg();
		System.out.println(obj.show());
	}
}
