# Lab Report 4

## Step 4
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/00a6f860-63b1-4ee6-afc7-9b93167f064f)

`<ctrl>` + `
 
ssh cs15lfa23ly@ieng6.ucsd.edu. `<enter>`

To open the terminal I typed `<ctrl>` and `. I then used the ssh command and typed my username to login to my account.

## Step 5

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/6aedc55d-b73d-4cfb-92f1-0d208edb1780)

git clone git@github.com:dantemccflurry/lab7.git. enter


`I used the git clone command and cloned the ssh url of my forked repository. `

## Step 6


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/b643a98f-9584-451c-9519-86c81ed58b87)





cd lab7 `<enter>`

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java `<enter>`

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests `<enter>`




`I used the cd command to change the directory into the lab7. I then ran the necessary javac line to compile the Junit and all java files. I then ran the java command on the Junit and ListExamplesTests.`

## Step 7

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/c26df563-ff8a-4c7f-902a-de9e6239d222)


43j

w

5l

x

i

2

`<esc>`

:wq `<enter>`


43j jumps 43 lines down the file to the line that has the bug. w shifts the cursor to the next word being index2. 5l shifts the cursor 5 to the left on top of the 2. x deletes the 2. i turns on insert mode and inserts the 2.
`<esc>` exits insert mode. :wq and `<enter>` to save the changes of the file.

## Step 8

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/01fda982-9c45-4d1b-aca5-a8b13427a625)


`<up>` `<up>` `<up>` `<enter>`
  
`<up>` `<up>` `<enter>`


I hit `<up>` three times then `<enter>` to get the javac command I ran earlier to compile all the files again after the changes. I then hit `<up>` two times and then `<enter>` to get the java command I ran to redo the tests.

## Step 9

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/4ed48578-d4d7-4b0a-b46b-bbc6cf15b2e2)


git add ListExamples.java `<enter>`

git commit `<enter>`

i I changed line 43 from index1 to index 2 `<esc>` :wq `<enter>`

git push `<enter>`


I staged the ListExamples.java file with git add and then committed it with the git committ command. I was prompted to give a commit message, in which I entered insert mode with i and typed the message. I then saved and
exited with :wq and pressed `<enter>`. Finally I pushed it to my repository with git push `<enter>`.



