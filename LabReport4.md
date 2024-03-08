## Step 1
![Image](vim-step1.png) <br>
Keys Pressed: Typed out `ssh tnghiem@ieng6.ucsd.edu <enter>` to log in.

## Step 2
![Image](vim-step2.png) <br>
Keys Pressed: Copied the `SSH` url on GitHub using `<ctrl-c>`. Then, typed out `git clone <ctrl-v><enter>` in the terminal to paste the link and clone it.

## Step 3
![Image](vim-step3.png) <br>
Keys Pressed: Typed out `cd <space> l <tab><enter>` to change into the `lab7` directory, then `bash t <tab><enter>` to run `test.sh`. This runs the tests in `ListExamplesTests.java` and shows that there are some tests failing.

## Step 4
![Image](vim-step4.png) <br>
Keys Pressed: Typed out `vim L <tab> . <tab> <enter>` to start editing the `ListExamples.java` file. Then, `/index1 <enter>` to search file, `<shift-n>` to go to the end, `e` to move to the end of the word, and `r2` to replace the `1` with a `2`. Finally, `:wq <enter>` to save and exit the file.

## Step 5
![Image](vim-step5.png) <br>
Keys Pressed: `<up><up><enter>`, the `bash test.sh` command was 2 up in the command history, so I used the up arrow to access it. 

## Step 6
![Image](vim-step6-part1.png) <br>
![Image](vim-step6-part2.png) <br>
Keys Pressed: Typed out `git add L <tab><enter>` to stage the edited file, `ListExamples.java`, for commit. Then, typed out `git commit <enter>`, where I did `i` to get into insert mode to type my message. After typing the message, I did `<esc> :wq <enter>` to exit insert mode and save and quit. Finally, typed out `git push <enter>` to push it to Github.
