# EECS 201 HW 6
uniqname: willruiz

## Question 1
``` 1
The '^' expression in grep makes grep take out the words that only have the grepped word as the beginning part of the entire word in the library. It treats the grep word as the head and looks for all words in the library with for this example 'pass' as the beginning part. An example would be be 'password'
```

## Question 2
``` 2
The '$' expression in grep makes grep take out words that have the grepped word as the end part of the word. It looks for words that have the grepped word as the tail part. An example would be 'encompass'
```

## Question 3
``` 3
The '.' expression makes grep treat the '.' as any character. It acts like a variable or wildcard placeholder. So in the case of 'p.ss', we can get 'piss', 'puss' and 'poss'
```

## Question 4
``` 4
grep -c ^...$ cracklib-small
```

## Question 5
``` 5
grep -c ^[a-z][a-z][a-z]$ cracklib-small
```

## Question 6
``` 6
The command basically counts the individual occurences of of each vowel in the entire library and output the count through echo. 
```

## Question 7
``` 7
grep -c -v -F -x -f british-english american-english | grep -c -v -F -x -f american-english british-english | awk '{SUM = $1 +$2} END { print SUM }'
```

## Question 8
``` 8
grep -c -v -F -x -f british-english american-english | grep -c -v -F -x -f american-english british-english | awk '{SUM = $1 +$2} END { print SUM }'
```

## Question 9
``` 9
The 'grep -v' command take everybut but the word that grep is being used on. It kind of invert searches and pulls all the words. Therefore 'grep -v ' \*' takesout all the lines that have a multiline comment header in the line and returns all the lines that are regualr expressions.
```

## Question 10
``` 10
No, if you use git grep on all untracked files that have not been added or commit, nothing shows up. But if you add or commit files, you can use git grep on them.
```

## Question 11
``` 11
Yes, after adding files to be staged, it shows up. You test it by having files unstaged, test git grep, then stage them by using git add, and then testing git grep again and see that git grep now works. 
```