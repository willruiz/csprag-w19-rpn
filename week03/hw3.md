# EECS 201 HW 3
uniqname: willruiz

## Question 1
``` 1
ls command stopped working. It says "-bash: ls: No such file or directory". I can still cd into other folders and directories, but it says it can't find any the files and list them out. 
```

## Question 2
``` 2
You have to specify which path to run the 'ls' command in because the current one is now empty. The example online was that "/bin/ls", now that there is no specified path, you have to manual input the path to the ls command. "export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin" also appearently returns your path to default. 
```

## Question 3
``` 3
pwd still works because it simply just echos the directory path. I think the command for 'pwd' does not need to be located in a bin.
```

## Question 4
``` 4
$? is the exit code of the last command executed. One useful exmample was if you were trying to run a command but an error came up, the $? variable may give a clue on why the command ran an error instead of running.
```

## Question 5
``` 5
$1 is the argument in index 1 in the executed script. For example, in resize.exe from project 2 in Fall 280, the argument for the project is "./resize.exe horses.ppm horses_400x250.ppm 400 250" $1 would return horses.ppm. 
```

## Question 6
``` 6 
#!/bin/sh
# Virtual Machine is too slow so I guess I'm wrecking my Windows.
g++ hello_world.cpp -o hello_world.exe
./hello_world.exe > output.txt
diff output.txt correct.txt
if [ $? -eq 0 ]
then
        echo "All tests passed."
else
        echo "Test failed. Expected out >>Hello World<<, got output >>" | cat output.txt | echo "<<"
fi
```

## Question 7
``` 7
You have to change your ~/.bash_profile using a text editor by entering "sudo vim ~/.bash_profile" this case using vim, and then enter the line "source ~/.bash_profile"
```

## Question 8
``` 8
Spent more than hour on this, mostly on Question 6, because I had to look up a lot of things.
```