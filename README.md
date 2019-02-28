# MobaXterm

[Download home edition from here.](https://mobaxterm.mobatek.net/download.html)

* Follow the installation wizard and install MobaXterm.

**Create Local Shell**

* Open MobaXterm and click Start Local Terminal on home page.

![](https://user-images.githubusercontent.com/22459679/53493856-70ef6080-3aad-11e9-9a7d-07c9419f611f.PNG)
 
 * Your local shell is ready.
 
![](https://user-images.githubusercontent.com/22459679/53494995-13104800-3ab0-11e9-9500-8c76a671ca79.PNG)

**Start new session**

* Click session from toolbar.

![](https://user-images.githubusercontent.com/22459679/53493859-7187f700-3aad-11e9-9964-5ab49853a6dc.png)

* Select SSH.
* Enter your remote host name. 
* If you want to specify username, click checkbox and write root.
* Click OK.

![](https://user-images.githubusercontent.com/22459679/53493858-7187f700-3aad-11e9-8b27-42b80e5b2dfb.PNG)

![](https://user-images.githubusercontent.com/22459679/53493857-7187f700-3aad-11e9-9d99-4690d3e691bc.PNG)


# Basic Linux Commands 

**pwd**

Print working directory; displays the name of current working directory.

![](https://user-images.githubusercontent.com/22459679/53398874-bd5a7380-39bb-11e9-92c8-0371d8025e06.PNG)

**ls**

Lists file and directories in the current working directory.

![](https://user-images.githubusercontent.com/22459679/53398871-bd5a7380-39bb-11e9-9779-0b312fc25f7c.PNG)

![](https://user-images.githubusercontent.com/22459679/53398872-bd5a7380-39bb-11e9-8c9a-9835b4f164ba.PNG)

**cd**

Changes the current directory.

![](https://user-images.githubusercontent.com/22459679/53399508-30181e80-39bd-11e9-9f64-02875776efb7.PNG)

**dir**

Used to get a list of all the files and folders in the current directory.


![](https://user-images.githubusercontent.com/22459679/53399503-2f7f8800-39bd-11e9-9d9f-3905a047341b.PNG)

**touch**

Creates blank file.

![](https://user-images.githubusercontent.com/22459679/53399504-2f7f8800-39bd-11e9-8162-e2896f3f4581.PNG)

**mkdir**

Create a new directory with a name.

![](https://user-images.githubusercontent.com/22459679/53399505-2f7f8800-39bd-11e9-86e9-648d93075f6e.PNG)

**mv**

Rename the files and directories.

![](https://user-images.githubusercontent.com/22459679/53399506-2f7f8800-39bd-11e9-97b7-6b91501ca913.PNG)

**rm**

It is used to remove a file. It doesn't remove directories.

![](https://user-images.githubusercontent.com/22459679/53399507-30181e80-39bd-11e9-9cb9-14d79a073913.PNG)


**rm -r directory**

rm command able to move directories with **-r** parameter.

![ ](https://user-images.githubusercontent.com/22459679/53407706-d66c2000-39cd-11e9-8add-eb04f0cb35de.PNG)

**rmdir**
 
 It is used to remove a directory.

![](https://user-images.githubusercontent.com/22459679/53407707-d704b680-39cd-11e9-8749-c76e373d6118.PNG)

**cat**

It is used to read, modify text files. Display file content.

![](https://user-images.githubusercontent.com/22459679/53407708-d704b680-39cd-11e9-83ee-6ac1e2aedff5.PNG)

**chmod**

Changes the permission of one or more files.

![](https://user-images.githubusercontent.com/22459679/53407711-d79d4d00-39cd-11e9-9672-ea3a503cd099.PNG)

**man**

It provides documentation about commands.

![](https://user-images.githubusercontent.com/22459679/53407716-d9ffa700-39cd-11e9-8a04-9879cf7117c2.PNG)

**less**

It is used to ..

![](https://user-images.githubusercontent.com/22459679/53407710-d79d4d00-39cd-11e9-9f86-bfe9d7b3f151.PNG)

**more**

![]()

**head**

![]()

**tail**

![]()

**vi**

![]()

**If Statement**

```
if [ <some test> ]
then
<commands>
fi
```

```
if [ <some test> ]
then
  <commands>
else
  <commands>
fi

```
```
if [ <some test> ]
then
<commands>
elif [ <some test> ] 
then
<different commands>
else
<other commands>
fi
```
```
if  [ <some test> ]; then
 <commands>
 elif [ <some test> ]; then
   <commands>
 else
   <commands>
fi
```

![ ](https://user-images.githubusercontent.com/22459679/53335485-a1e45f80-390c-11e9-9ae1-0006f52487e3.PNG)

![ ](https://user-images.githubusercontent.com/22459679/53335491-a4df5000-390c-11e9-95df-db04ef94f837.PNG)

Result

![ ](https://user-images.githubusercontent.com/22459679/53335487-a3ae2300-390c-11e9-9a80-c26831d76817.PNG)

 ![ ](https://user-images.githubusercontent.com/22459679/53335632-099aaa80-390d-11e9-90f8-3ab29a8577fd.PNG)

**For Loop**

```
for var in <list>
do
<commands>
done
```

![ ](https://user-images.githubusercontent.com/22459679/53334227-32b93c00-3909-11e9-868f-d307f06a0d0f.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53334228-3351d280-3909-11e9-83d0-e90527222c41.PNG)

**Using for loop with commands**

![ ](https://user-images.githubusercontent.com/22459679/53334229-3351d280-3909-11e9-948a-d97feafe73b2.PNG)

Result

![ ](https://user-images.githubusercontent.com/22459679/53334230-3351d280-3909-11e9-9340-01ce19160406.PNG)

**Using with files**

![ ](https://user-images.githubusercontent.com/22459679/53334231-3351d280-3909-11e9-88c0-f12afbd69dc2.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53334232-33ea6900-3909-11e9-8064-ed6355efb7d6.PNG)
 
 **Printing the file names**
 
 ![ ](https://user-images.githubusercontent.com/22459679/53334567-44e7aa00-390a-11e9-94f1-72f551aa081f.PNG)
 
 Result
 
 ![ ](https://user-images.githubusercontent.com/22459679/53334589-49ac5e00-390a-11e9-9689-4e36c3a66e7c.PNG)
 
 **Nested for structure**
 
 ```
for var in <list>
do
 for var in <list>
 do
 <commands>
 done
done
```


![ ](https://user-images.githubusercontent.com/22459679/53334590-4a44f480-390a-11e9-91d2-f92b620d1ce4.PNG)

Result

![ ](https://user-images.githubusercontent.com/22459679/53334591-4a44f480-390a-11e9-8c69-6ce0a4b73de8.PNG)

**Nested for structure 8x8 chess table**

![ ](https://user-images.githubusercontent.com/22459679/53334592-4a44f480-390a-11e9-8e90-5d6f967350a2.PNG)

Result

![ ](https://user-images.githubusercontent.com/22459679/53334594-4a44f480-390a-11e9-89cc-f4326c44a300.PNG)

**Test conditions**

```
[some test condition] && true_ || false_
```

 ```
 #!/bin/sh
[ $X -ne 0 ] && echo "X isn't zero" || echo "X is zero"
[ -f $X ] && echo "X is a file" || echo "X is not a file"
 ```

![ ](https://user-images.githubusercontent.com/22459679/53335469-9b55e800-390c-11e9-9b6c-6cc4ef524cdf.PNG)


 Result

 ![ ](https://user-images.githubusercontent.com/22459679/53335476-9f820580-390c-11e9-940f-d3404b4b7674.PNG)
 
 ```
 #!/bin/sh
if [ "$X" -lt "0" ]
then
  echo "X is less than zero"
fi
if [ "$X" -gt "0" ]; then
  echo "X is greater than zero"
fi
[ "$X" -le "0" ] && \
      echo "X is less than or equal to  zero"
[ "$X" -ge "0" ] && \
      echo "X is greater than or equal to zero"
[ "$X" = "0" ] && \
      echo "X is the string or number \"0\""
[ "$X" = "hello" ] && \
      echo "X matches the string \"hello\""
[ "$X" != "hello" ] && \
      echo "X is not the string \"hello\""
[ -f "$X" ] && \
      echo "X is the path of a real file" || \
      echo "No such file: $X"
[ "$X" -nt "/etc/passwd" ] && \
      echo "X is a file which is newer than /etc/passwd"

 ```
 
 **While Loop**
 
```
while [ <some test> ]
do
<commands>
done
```

 
**Using while with reading a text files**

![ ](https://user-images.githubusercontent.com/22459679/53336192-a90c6d00-390e-11e9-83fd-8fcff15921af.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336197-ab6ec700-390e-11e9-8512-4327c99cbe8a.PNG)
 
 **Reading a file with separate files**

![ ](https://user-images.githubusercontent.com/22459679/53336198-ac075d80-390e-11e9-8f1f-29ec6ade5e11.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336201-ae69b780-390e-11e9-9177-c2c3ea0092a3.PNG)
 
 **Reading etc/passwd files**

![ ](https://user-images.githubusercontent.com/22459679/53336202-ae69b780-390e-11e9-9efa-23d872219453.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336203-ae69b780-390e-11e9-9c09-f071b929f2e7.PNG)
 
 **Reading etc/passwd with using separator**
 
 IFS: ....

![ ](https://user-images.githubusercontent.com/22459679/53336204-af024e00-390e-11e9-8bb7-7e0b267b3457.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336205-af024e00-390e-11e9-96b6-2103b6575ef8.PNG)
 
 
 **Using while loop with case**
 
 ```
 while 
 do
 ..
  case $var in
  case 1)....;;
  case 2)....;;
  ..
  ..
  esac
 done 
 ```

![ ](https://user-images.githubusercontent.com/22459679/53336616-ddccf400-390f-11e9-8ae3-dd6bc886a56d.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336619-e02f4e00-390f-11e9-89bb-a851370fe624.PNG)
 ![ ](https://user-images.githubusercontent.com/22459679/53336621-e1607b00-390f-11e9-8d91-783b94d66000.PNG)
 ![ ](https://user-images.githubusercontent.com/22459679/53336622-e291a800-390f-11e9-92ad-6c6df5168b4a.PNG)

 **Select command**
 
 ```
 select var in <list>
do
 case $var in
  case1)....;;
  case2)....;;
  ...
  ....
  case*)....;;
done
```
 
![ ](https://user-images.githubusercontent.com/22459679/53336974-11f4e480-3911-11e9-9414-9e12fec4baa2.PNG)

Result

 ![ ](https://user-images.githubusercontent.com/22459679/53336975-11f4e480-3911-11e9-8840-7905bc269f93.PNG)
