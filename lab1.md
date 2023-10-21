# Lab Report 1

## `cd` 

1) `cd`

![cd-no-arg](https://github.com/shinaegyo/cse15l-lab-reports/assets/137027086/e9d686e6-8667-4d29-8e3b-e9f7615c634e)
The working directory was `/home` and I got this output because whenever I cd with no arg, I return back to home.

2) `cd lecture1` 

![Image](cd-directory.jpg)
The working directory was `/lecture1/messages` and I got this output because I changed the directory from home into lecture and into messages. There are no errors.

3) `cd /home/lecture1/messages/ko.txt`

![cd-file](https://github.com/shinaegyo/cse15l-lab-reports/assets/137027086/e38a6fa5-250d-42a9-b495-a238237d10be)
The working directory is /home and I got no directory because I changed the directory into a file called ko.txt which is a file and not a a directory. There is an error because the file is not a directory.

## `ls` 

1) `ls`

![Image](ls-no-arg.jpg)
The working directory is home because the list of options from home is only the lecture1 directory. There is no error.

2) `ls lecture1`

![Image](ls-directory.jpg)
The working directory is home because I did not change the directory rather just asked the compiler to provide a list from the lecture1 directory. There is no error.

3) `ls lecture1/messages/en-us.txt`

![Image](ls-file.jpg)
The working directory is home because I did not change the directory rather just asked the compiler to provide a list. There is no error.

## `cat` 

1) `cat`
   
<img width="199" alt="cat-no-arg" src="https://github.com/shinaegyo/cse15l-lab-reports/assets/137027086/c30690f8-7039-4a16-a065-b968571e9250">
The working directory is home because it does not change the directory and I got no output because there is nothing to be shown with just cat. Even though I inputted james shin, I can infinitely input anything and there will be no change in the directory or path. To get out of the loop, I did control D and I returned back to `/home` There is no error message. 

2) `cat lecture1`

![Image](cat-directory.jpg)
The working directory is home because it does not change the directory and I got the output because it shows that lecture1 is a directory and not a file. There is an error message because cat prints out whatever solution there is in the code but it shows that lecture1 is just a directory.

3) `cat lecture1/messages/ko.txt`

![Image](cat-file.jpg)
The working directory is `/home` because it does not change the directory and I got the output because it shows that hello world in Korean is translated to the output I got as `cat` will print out the output of the general path. If I did `cat lecture1/messages/en-us.txt`, it will print out Hello World! because I `cat` into that path. There is no error message.  
