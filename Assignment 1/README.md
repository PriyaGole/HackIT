## Assignment 1

You're given a [file](./Assignment_1/i_am_hiding_stuff.txt). It's too long for you to go through. But there are a few pieces of information lying in midst that string that you need to find.

1. The word "HACK"
2. A 10 consecutive digit Number
3. A link based on File Transfer Protocol at Port 8080
4. A substring of the form "hackIT{...}"

It's guaranteed that the formats would be like this, with no other such substrings in that file

The problem is you're only provided the access of `/bin/bash` or `/usr/bin/python3` (i.e. you can use bash or python as languages, with these being included in the she-bang line), with no other string search binaries or libraries. It means you **can't** use tools like `grep`, `awk`, `tr`, `sed`, `re`, etc. Only i/o tools or libraries and pure scripting.  
So create 4 scripts of name `1.sh`, `2.sh`, `3.sh`, and `4.sh` for the corresponding problems, mark them as executables, such that running them directly outputs the needed strings.

> Bonus : Apart from returning/echo-ing values, return/echo their line numbers as well.

You've to submit a directory of name `XXXXXX_Your_Name` with `XXXXXX` being your roll number. Keep all 4 scripts and any bonus related writeup inside that directory. Commit this folder **inside [Assignment_1](./Assignment_1/)** and make a PR on this repo's `main` branch ONLY.

I'm giving a choice between `bash` or `python`, because this will decide how comfortable you get in either. You'll eventually find that mostly all languages can replace each other, so it comes down to convenience and speed.

> NOTE: A bash based submission will be scored higher (x1.2 score) than the corresponding python based. This is because you're meant to practice bash scripting. You can opt for using both languages partly (1 and 2 for bash, 3 and 4 for python).

Do remember that judgement is on you using BASH/Python3 with no pre-built string manipulation commands. Inefficient but working code **is acceptable** for this assignment. Use any amount of nesting you want! (Just that it should run within 5 seconds).

---------------------------------------------------------------------------------------------------------------------------------------------------------------

# Assignment 1 Submission

To execute the n<sup>th</sup> script file (where n = 1, 2, 3,  or 4), open a (linux) terminal:
1. Go to the corresponding directory.
2. Run the following command:

``` sh
./n.sh i_am_hiding_stuff.txt
```

---
