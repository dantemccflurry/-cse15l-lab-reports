# Lab Report 1
---
## `cd command`
**cd command w/o arugment**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/729b6bdf-f0ad-4538-a009-501a8ec49482)

`The working directory was /home. The reason this is the output is because the cd command changes the directory back to the home directory, thus with no arugment and/or a preexisting directory beyond just the home directory, it will return back. In this case, it was already the home directory /home. This is not an error.`

**cd command w/ directoy as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/0d36cff9-b067-4a66-9757-72235b2a345a)

`The working directory was /home when the program was run. The reason for this output is becasue the cd command changed the directory to the argument given, that being Lecture1, thus the working directory now is /home/lecture1. This output is not an error.`

**cd command w/ file as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/567d2239-569f-4bb1-9bc0-86a7bce7f7ba)

`The working directory was /home/lecture1. The reason for this output is because the argument messages/en-us.txt is not a directory. A directory would be if the argument was just messages or /home/lecture1/messages. This output is an error becasue the argument is not a directory, thus returns a message pointing out the issue.`

---

## `ls command`

---
**ls command w/o argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/ba5e48dc-b05d-4724-a5f1-3ee05e1e2e72)

`The working directory at the time is /home. The reason for the output is becasue ls lists the files and folders of the path, thus Lecture1 would be the continuation of the path. This is not an error.`

**ls command w/ directory as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/15ef9a1a-285f-4127-b49b-431c75ee2fc9)

`The working directory at the time is /home. The reason for the output is since ls returns the files and folders of the path, the next files and folders of /home/lecture1 would be the messages, java files, and readme. This output is not an error. `

**ls command w/ file as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/e6fcc6ce-7ac9-4c3b-a9a4-727922410473)

`The working directory at the time is /home. The reason for the output is that there are no more files and paths after /home/lecture1/messages/en-us.txt, thus it returns the directory with the argument. This output is not an error.`

---
## `cat command`

---
**cat command w/o argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/78009ab8-3fbb-48ea-ac25-cab9b19a2225)


`The working directory is /home. The reason for the output is that cat prints the file, however there is no file to print. Instead the terminal waits for a input and returns the user input infintely amount of times until the user exits out manuelly. This output is not an error as this is the expected output.`

**cat command w/ directory as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/955440a3-0005-4d9b-bb0a-78848647f037)

`The working directory is /home. The reason for the output is due to Lecture1 being a directory and not a file, thus it doesn't print anything. This output is not an error.`

**cat command w/ file as argument**

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/952e1bd7-dcc0-4cb5-a79b-43c63e48089f)

`The working directory is /home. The reason for the output is since /home/lecture1/messages/en-us.txt is a file, it prints what is in the file. This output is not an error.`










