# Insta-hacking<br>

<h2>Explanation</h2>
In BruteForce attack method, which the program keeps putting in the passwords until we get the right one. I know, the program puts the password over and over again, it will take a long time, it might fail, but it is better than not doing it. There is another way, By using Dictionary in brute force method. We provide a .txt file containing possible password to try.

<br>
<h2>Lets begin</h2>
<h3>Step 1 - clone it</h3>
So first, we will need to get the program that keeps putting in the password.
To do that, simply type : <br>

```
git clone https://github.com/hardhikgupta/Insta-hacking.git
```
<br>
Above command will clone the program to your computer.Now you need to chmod the file and go to the directory of the program, so type :
chmod -R 755 Instagram && cd Instagram

<h3>Step 2 - Execute the Program</h3>
Well, we know there are three things inside the folder, “Core”, “README.md” and “instagram.py”.The executable program here is “instagram.py”.We need to execute the program now, by typing :
<br>

```
python3 instagram.py
```
It wont do anything as of now and will throw an error, It is because we do not have the txt file.
Remember, this is a BruteForce Dictionary attack, we need to give it a lists of passwords so the program knows which password it should put in.

<h3>Step 3 - Create A password List </hr>
<br><br><br>
<h3>Final Step </h3>
Yes, there is the text file in the folder! lets execute the program by :
<br>

```
python3 instagram.py Username Thetextfile.txt
```
Now we are at the end! The BruteForce attack has started, it will say the attempts and what password it is currently trying.
Well, It would take a long time.
