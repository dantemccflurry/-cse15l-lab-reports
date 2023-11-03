# Lab Report 3
--- 
## PART 1 
---

**Buggy Code in Question**
---

static void reverseInPlace(int[] arr) {
   
    for(int i = 0; i < arr.length; i += 1) {
     
      arr[i] = arr[arr.length - i - 1];
    
    }
  
  }

 
  **Failure Inducing Test**
  ---

public class ArrayTests {

	@Test
 
	public void testReverseInPlace() {
 
    int[] input1 = {3,2,1};
    
     ArrayExamples.reverseInPlace(input1);
   
    assertArrayEquals(new int[]{1,2,3}, input1);
    
	}

 **Non-Failure Inducing Test**
 ---
 public class ArrayTests {

	@Test
 
	public void testReverseInPlace() {
 
    int[] input1 = {3};
    
    ArrayExamples.reverseInPlace(input1);
    
    assertArrayEquals(new int[]{3}, input1);
    
	}

 **Symptom for Faiure Inducing Test**
 ---
 ![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/c44dc430-c3fc-4516-8274-4fee2a688e4c)


 **Symptom for Non-Failure Inducing Test**
 ---
 ![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/fc4b89d2-9177-44f5-9b7f-9e7f354468b6)

 **The Bug**
 ---
 **Before**
 
  static void reverseInPlace(int[] arr) {
   
    for(int i = 0; i < arr.length; i += 1) {
     
      arr[i] = arr[arr.length - i - 1];
    
    }
  }
 

 **After**
 
 static void reverseInPlace(int[] arr) {
 
    int temp;
   
    for(int i = 0; i < arr.length/2; i += 1) {
      
      temp=arr[i];
      
      arr[i] = arr[arr.length - i - 1];
      
      arr[arr.length - i - 1]=temp;
    
    }
  
  }

 **Reason**
 ---

 `The reason why my fixes address the issues is becasue when the orignal code swapped the values, it never saved the arr[i] value, thus it is lost forever.
 My code fixes the issue by saving arr[i] into a temp and swapping right after arr[i] is replaced with the arr[i-i-1]. I cut the length of the loop by half since two values are changed at a time, thus there is no reason to go through the whole list.`

## PART 2
---
**Find Command-Options**
---

**-iname**

[Source for this command-line option](https://www.redhat.com/sysadmin/linux-find-command)

`find technical/911report -iname "*1*.txt"`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/5df2bb4f-acb3-481e-be0b-eb0a6d2e0358)

`find technical/plos -iname "*pmed*.txt" `

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/f6e5d8fb-3564-4b8a-92f5-e30df61508f3)

`Iname option searches parts of the title and matches it with the given aruguement and returns all files with that contain the argument in its name. In these examples they use  technical/911report -iname "*1*.txt" and find technical/plos -iname "*pmed*.txt" and they return all the files that contain those arguments respectively. This is command-line option is good incase you don't remember the exact name of the file, but parts of it, thus it can narrow down the search with the find command. This is better than using the find command and having to look through each file to see which one your looking for.`

**- type f**

[Source for this command-line option](https://www.redhat.com/sysadmin/linux-find-command)

`find technical/911report -type f`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/4567bf9a-e377-4729-a7b0-d4ce76099c72)

`find technical/government/Post_Rate_Comm/ -type f`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/7250597b-d1de-47f2-9e2f-0579e582973c)

`Type f finds all files in the given working directory. In this case,find technical/911report -type f and find technical/government/Post_Rate_Comm/ -type f are used to find all files in their respective directories. This option is another good way to find files, but rather than search by name or something in the name, you can search by file type. If you have a directory with many different types of files that potentially have similar names, then this command can shorten that search.`

**- type d**

[Source for this command-line option](https://www.redhat.com/sysadmin/linux-find-command)

`find technical/ -type d`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/6bd38a8f-fc55-45ce-ad4a-2df748786c1d)

`find technical/911report -type d`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/259a7130-ecc2-47fb-9755-f00e28b1db32)

`Type d searches for all directory paths from the given path. In this case it searches from both technical/ and technical/911report and returns all possible directory paths. However, it returns the working directory when given technical.911report since there are no more directory paths in it. This command is useful for finding paths that can be useful for searching for a file. It is a good replacement for ls commanding every path to find all the paths and instead with one command, you can see it all.`

**- empty**

[Source for this command-line option](https://www.redhat.com/sysadmin/linux-find-command)

`find technical/ -empty`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/0e6bea93-290f-4e1f-ac22-a4d9d5e007ca)

`find technical/911report -empty`

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/cca2277b-8893-4ef6-b583-79859ecfe08b)

`Empty searches for all empty files or directories that contain no characters or files, which can be useful for trying to organize a workspace. In these cases, find technical/ -empty returned three files that I made that contained nothing in them. However, with find technical/911report -empty, nothing was returned since there are no empty files in that directory.`













 

