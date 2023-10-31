# Lab Report 2
---
##  **PART 1**
## *Code for StringServer*
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/50ec7a5c-0732-4d2f-8431-e44b945cdc76)
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/9a76434b-4707-4409-b3dd-55c225a384d1)



---
## *StringServer using add message with My name is Dante*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/1d69e49e-601c-449d-bfc2-f4caaf2a2008)

`The methods called in this example are `List(ArrayList<String>arr)`, `sentenceConverter(String x)` and `handleRequest(URI url)`. `List` takes in an `arraylist` with all the entries that have been added to the server. The class
has a field named `entries` that stores all of them that starts off empty and another class field named `start` which acts as a way to build on the current set of `strings` temporarly. `sentenceConverter` takes a `string`, usually one from the `entries` list, and formats the `string` if it is a sentence. `handleRequest` examines the `url`
and checks if the user has appeneded the correct request to update the website. In `handleRequest`, the methods `List` and `sentenceConverter` are called if the user appended correctly to the `url`, thus it adds the
input and any previous input made by the user. `List` is the method that prints out all previous `strings` made by the user stored in entries with the `index+1` being printed in front of each string to show when the string was added.
sentence. As each method is called after a user enters a new string, the ArrayList entries increases in size has the user String is added to the list. The class field start is temporarly updated with the new string added from the user, which is then stored in list for later use such as printing all strings. In this case, the string My name is Dante is added to entries and reprinted on the screen next to 1.`


---
## *StringServer using add message with Dante*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/cff6d4b9-d266-450c-a15a-49b9fb5af9b8)

`The methods called in this example are List(ArrayList<String>arr), sentenceConverter(String x) and handleRequest(URI url). List takes in an arraylist with all the entries that have been added to the server. The class
has a field named entries that stores all of them that starts off empty. sentenceConverter takes a string, usually one from the entries list, and formats the string if it is a sentence. handleRequest examines the url
and checks if the user has appeneded the correct request to update the website. In handleRequest, the methods List and sentenceConverter are called if the user appended correctly to the url, thus it adds the
input and any previous input made by the user. List is the method that prints out all previous strings made by the user stored in entries with the index+1 being printed in front of each string to show when the string was added.
sentence. In this case, Dante is added to the field entries and the List method reprints all the strings, on their repsective lines, in front of their respecticve indices+1.`

---
## PART 2
---

## *Path to Private ssh Key*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/f3ad31d1-e1b7-49e0-94c6-1c8a6b3e8681)

---
## *Path to Public ssh Key*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/22e502a9-82b4-498a-8ec7-a720657d5698)

---
## *SSH Login with no Password*


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/dd4f2ae9-426c-435c-8ef3-9718c07277f2)

## PART 3
---
`I learned a shortcut to login to my ssh account without inputing the login by using new commands such as mkdir to make a directory for my private key and scp to copy my key to my computer. I learned how to host a server on my own computer instead of on the computers in the basement by using the code provided by in the wavelet files NumberServer and Server. With that, I also learned how to add on to a url invloving queries to manipulate the servers I hosted. `







