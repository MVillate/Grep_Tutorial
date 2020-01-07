# Grep_Tutorial
Grep Tutorial and Examples

- Search in the current directory recursively (r: Recursive, i: Ignore case, l: only filename will be shown)
~~~ 
grep -ril "ISB-RT01" .
~~~
- Search in a different directory
~~~ 
grep -ril "prg-RT01" iTerm2_Logs/
~~~
- Search the whole word in a file, and the line number where it is (w: whole, n: line number)
~~~
grep -win "bdp-rt01" 20200107_174114.Default.w0t0p0.68FF5377-D521-4D0E-86EF-91E4B7C78ED5.22162.2437553506.log
~~~
- Searching in a folder a specific command:
~~~
$ grep -irn "bdp-rt01#show ip int brief" .
./20200107_174114.Default.w0t0p0.68FF5377-D521-4D0E-86EF-91E4B7C78ED5.22162.2437553506.log:21:BDP-RT01#show ip int brief
~~~
