JythonExecutable
================
Skeleton of a project for making an executable jar using Jython.

main.resources/__run__.py
===========
put default runnable code here.  Do NOT use if name == __main__, bas this will not work because __name__ is set by the jar name, not __main__

main.resources.Lib
==================

Put your other python code here.  It is executable by passing "-m classname" to the jar file.

For whatever reason, this loads faster than using __run__.py