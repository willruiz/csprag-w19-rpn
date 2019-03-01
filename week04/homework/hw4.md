# EECS 201 HW 4
uniqname: willruiz

## Question 1
``` 1
We are using Vim
A. gg=G
B. Hit 'v', then select the block of code, then hit '<' to deindent the block of code. 
```

## Question 2
``` 2
:split, 'ctrl-w' up or down, :edit [filename]
```

## Question 3
``` 3
After typing ':make', type ':cwindow', and the KatsBadcode. This allows the user to navigate through the errors on the shell instead of directly through the vim texteditory.
```

## Question 4
``` 4
Use triple quotes '''. Even though the complier does not ignore it, it treats the lines in triple quotes as code that isn't executed. 
```

## Question 5
``` 5
For the example give, one that may work would be qa$i[right arrow]','[esc]0daw$p0i[del]'"first": "'[esc]wwi'"'[right arrow x2]'"last": "'$i[right arrow]'"'q

In general, to record press 'q' then press a key to save the macros such as 'w'. To replay it hit "@w". To replay 50 times, press "50@w".
```

## Question 6
``` 6
A. Hit '%' to jump to matching bracket
B. :!ls in Vim
```