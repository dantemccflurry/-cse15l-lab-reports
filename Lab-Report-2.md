# Lab Report 2
---
##  **PART 1**
## *Code for StringServer*
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/50ec7a5c-0732-4d2f-8431-e44b945cdc76)
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/9a76434b-4707-4409-b3dd-55c225a384d1)



---
## *StringServer using add message with My name is Dante*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/1d69e49e-601c-449d-bfc2-f4caaf2a2008)

The methods called in this example are `List(ArrayList<String>arr)`, `sentenceConverter(String x)` and `handleRequest(URI url)`. `List` takes in an `arraylist` with all the entries that have been added to the server. The class
has a field named `entries` that stores all of them that starts off empty and another class field named `start` which acts as a way to build on the current set of `strings` temporarly, but starts off as empty to begin with. `sentenceConverter` takes a `string`, usually one from the `entries` list, and formats the `string` if it is a sentence. `handleRequest` examines the `url`
and checks if the user has appeneded the correct request to update the website. In `handleRequest`, the methods `List` and `sentenceConverter` are called if the user appended correctly to the `url`, thus it adds the
input and any previous input made by the user to `entries` by updating the `start` field with the new string. `List` is the method that prints out all previous `strings` made by the user stored in entries with the `index+1` being printed in front of each string to show when the string was added.
sentence. As each method is called after a user enters a new `string`, the `ArrayList` entries increases in size has the user `String` is added to the `list`. The class field `start` is temporarly updated with the new `string` added from the user, which is then stored in `list` for later use such as printing all strings. In this case, the `string My name is Dante` is added to `start` as well as the `entries` field by using `start` and reprinted on the screen next to 1. `Entries` now has a size of one and `start` holds the value `My name is Dante`.


---
## *StringServer using add message with Dante*

![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/cff6d4b9-d266-450c-a15a-49b9fb5af9b8)

The methods called in this example are `List(ArrayList<String>arr)`, `sentenceConverter(String x)` and `handleRequest(URI url)`. `List` takes in an `arraylist` with all the entries that have been added to the server. The class
has a field named `entries` that stores all of them that starts off empty and the string class field `start` starts empty that is temporarly updated everytime a new entry is added by the user. `sentenceConverter` takes a `string`, usually one from the `entries` list, and formats the `string` if it is a sentence. `handleRequest` examines the url
and checks if the user has appeneded the correct request to update the website. In `handleRequest`, the methods `List` and `sentenceConverter` are called if the user appended correctly to the url, thus it adds the
input and any previous input made by the user to `entries` by updating the `start` field with the new string. `List` is the method that prints out all previous strings made by the user stored in entries with the `index+1` being printed in front of each string to show when the string was added.
sentence. In this case, `entries` already has the sentence `My name is Dante` as one of the values it holds at `index 0`. `Start` is made back to an `empty string` during the call, but is updated to hold the `string Dante` and add it to `entries`. After Dante is added to entries, `list` is called upon to print all the `strings` stored in `entries`, that being `My name is Dante` and `Dante` on seperate lines respectively. `Entries` now had the two strings as its elements and `start` holds the string `Dante`.

---
## PART 2
---

## *Path to Private ssh Key*
---
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/d45f8208-42bd-4bd0-ae6d-d5773aaf9cde)


```The Path to my private key is /c/Users/dante/.ssh/id_rsa. The file id_rsa from the ls called with the working directory /c/Users/dante/.ssh is the file that contains my private key.```

---
## *Path to Public ssh Key*
---
![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/a01d3279-5750-4888-9603-4c0695d293f7)

```The path to my public key is /home/linux/ieng6/cs15lfa23ly/.ssh/authorized_keys. The file seen from the ls with the working directory /home/linux/ieng6/cs15lfa23ly/.ssh called authorized_keys is the file that contains my public key.```


---
## *SSH Login with no Password*


![image](https://github.com/dantemccflurry/-cse15l-lab-reports/assets/130246353/dd4f2ae9-426c-435c-8ef3-9718c07277f2)

## PART 3
---
`I learned a shortcut to login to my ssh account without inputing the login by using new commands such as mkdir to make a directory for my private key and scp to copy my key to my computer. I learned how to host a server on my own computer instead of on the computers in the basement by using the code provided by in the wavelet files NumberServer and Server. With that, I also learned how to add on to a url invloving queries to manipulate the servers I hosted. `







