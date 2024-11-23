### Table of Contents

- [Table of Contents](#table-of-contents)
- [What is Competitive Programming(CP)?](#what-is-competitive-programmingcp)
- [Problems and Algorithms](#problems-and-algorithms)
- [What's in a Problem?](#whats-in-a-problem)
- [How to Solve a Problem?](#how-to-solve-a-problem)
- [The Ultimate Question: Why should I start Competitive Programming?](#the-ultimate-question-why-should-i-start-competitive-programming)
- [The Secret](#the-secret)
- [Seriously vs Sincerely](#seriously-vs-sincerely)
- [What Progress is Really Like](#what-progress-is-really-like)
- [Which language should I use for CP?](#which-language-should-i-use-for-cp)
- [Where to write codes? What are the best IDEs?](#where-to-write-codes-what-are-the-best-ides)
  - [Sublime Text Setup](#sublime-text-setup)
    - [My Windows Build](#my-windows-build)
    - [My Mac Build](#my-mac-build)
    - [bits/stdc++.h file not found on Mac](#bitsstdch-file-not-found-on-mac)
    - [Infinite Loop](#infinite-loop)
  - [VS Code Setup](#vs-code-setup)
- [Useful Keyboard Shortcuts](#useful-keyboard-shortcuts)
  - [General](#general)
  - [Sublime Text Specific](#sublime-text-specific)
- [What is a Contest?](#what-is-a-contest)
- [Competitive Programming Platforms](#competitive-programming-platforms)
- [Verdicts](#verdicts)
- [What to do if I don't know how to solve a problem?](#what-to-do-if-i-dont-know-how-to-solve-a-problem)
- [How to Read Problem Statements?](#how-to-read-problem-statements)
- [How to practice a problem efficiently?](#how-to-practice-a-problem-efficiently)
- [Kidlin's Law](#kidlins-law)
- [Number of Problems](#number-of-problems)
- [Machine Learning](#machine-learning)
- [ICPC and National Contests](#icpc-and-national-contests)
- [FAQ](#faq)
- [Books](#books)
- [Important Notes](#important-notes)
- [Tutorial](#tutorial)
- [Life Hack(if you are from Bangladesh)](#life-hackif-you-are-from-bangladesh)
- [Code Library](#code-library)
- [Common Mistakes](#common-mistakes)
- [How to Debug](#how-to-debug)
- [Stress Testing](#stress-testing)
- [Coding Style](#coding-style)
- [More About Contests](#more-about-contests)
  - [Codeforces](#codeforces)
  - [AtCoder](#atcoder)
  - [CodeChef](#codechef)
  - [Should I Participate in Contests?](#should-i-participate-in-contests)
- [Virtual Contests](#virtual-contests)
- [Useful Tools](#useful-tools)
- [Similar Tutorials](#similar-tutorials)

### What is Competitive Programming(CP)?

Writing code to solve problems or tasks is the essence of programming. Competitive programming turns this into a sport, with competitors competing (typically online) to solve a bunch of such problems in a restricted period of time.

"A programming competition generally involves the host presenting a set of logical or mathematical problems, also known as puzzles, to the contestants (who can vary in number from tens to several thousand), and contestants are required to write computer programs capable of solving each problem. Judging is based mostly upon several problems solved and time spent for writing successful solutions." - Wikipedia

### Problems and Algorithms

A problem is often based on arithmetic, logic, and/or _algorithms_ and looks somewhat like [this](https://cses.fi/problemset/task/1068). Such challenges often include a statement (detailing the task), the input and output format, and input, time and memory constraints.

<br>

But what is an Algorithm? "An algorithm is a step-by-step procedure or a set of rules for solving a specific problem or accomplishing a specific task. It is a precise and well-defined sequence of instructions that can be followed to solve a problem or perform a computation."

Here's an algorithm for brushing your teeth:

- Gather your toothbrush, toothpaste, and a cup of water.
- Wet your toothbrush with water.
- Squeeze a small amount of toothpaste onto the toothbrush.
- Put the toothbrush in your mouth and scrub each section of your teeth for some time.
- Rinse your mouth with water.
- Rinse your toothbrush with water and put it back in its place.
- Wipe your mouth with a towel if necessary.

Just like a computer algorithm, this is a series of specific steps you follow to accomplish a specific task - in this case, brushing your teeth. If you follow these steps in the right order, you will have successfully cleaned your teeth! This illustrates the core principle of an algorithm: a set of instructions that, when followed in sequence, help you accomplish a task or solve a problem.

<br>

**Problem-Solving is all about applying algorithms to solve problems.**

### What's in a Problem?

- **Problem Statement:** This defines the task that needs to be solved.
- **Constraints:** These indicate the range or size of the input that your program should be able to handle.
- **Input and Output Instructions:** These detail what and how your program should read as input and write as output.
- **Sample Input and Output:** There will be a few sample inputs and outputs to help you understand the problem better.
- **Notes:** These supplement the problem statement by demonstrating scenarios and clarifying the task.
- **Test Cases:** Your program should be able to pass these scenarios to be considered accepted.
- **Limits:** These indicate the time and memory limits that your program should not exceed.

<br>

You are required to submit a solution in a supported programming language of your choice. The solution should execute within the stated time and memory limits.

Your solution will be run against a series of test cases once you submit the solution. The test cases will be _exactly_ as the input format stated in the problem statement. To get accepted, your solution must generate the correct output for **all** test cases.

Note that the test cases are hidden and you will not be able to see them before getting accepted. But you can 100% trust that the test cases are correct and follow the input format stated in the problem statement and the constraints are also correct.

<br>

Why do the solutions need to be run against a series of test cases? Because one problem can be solved in many ways and in many languages. So it's impossible to check the correctness of a solution by looking at the code. So the solution is: let's say I have created the problem, I know the correct solution and I have created a series of test cases that will check the correctness of the solution. So when you submit your solution, it will be run against my test cases and if your solution generates the same output as mine, then your solution will be accepted.

And this is why there should be input constraints because a solution may work on integers, but may not work on floating points. For example, if the input is an integer $n$, then the constraint is like this: $1 \le n \le 10^9$. This means that the input will be an integer and it will be between $1$ and $10^9$. So if you are taking the input as an integer, then you should make sure that your program can handle all integers between $1$ and $10^9$.

And this is why there should be time and memory constraints because a solution may work on small inputs, but may not work on large inputs. If your solution takes $1$ year to run, then I won't wait for $1$ year to check the correctness of your solution!
And if your solution takes $100$ GB of memory to run, then I won't buy $100$ GB RAM to check the correctness of your solution! That's why there should be memory constraints.

<br>

### How to Solve a Problem?

Solve this problem: [smash me](https://cses.fi/problemset/task/1068)

1. **Understand the problem statement:** This is crucial. Make sure you understand what the problem is asking for, the constraints you have to work with, and the input and output formats. Misunderstanding any part of the problem can lead to a solution that doesn't work.

2. **Break It Down:** Most problems are easier to solve when broken down into smaller, manageable parts. Identify the different components of the problem and try to understand how they relate to each other.

3. **Make a Plan/Algorithm:** Once you've broken down the problem, you should have a better idea of how to solve it. Formulate a strategy for solving the problem. Use pen and paper to write down the steps you need to take to solve the problem. **You should have a clear idea of your solution before you start writing the code for it.**

4. **Write the Code:** Once you have a solid plan, you can start coding. Write your code carefully, keeping it as clean and clear as possible. This will make it easier to debug and improve later.

5. **Test Your Solution:** Once you've written your code, you should test it against the sample test cases provided in the problem statement. If your solution passes all the sample test cases, you can submit it. You can also try to come up with your own test cases to check your solution.

6. **Debug and Improve:** If your solution doesn't pass all the sample test cases, you should debug it. Debugging means finding the bugs/errors. Go through your code line by line and check if it's doing what you expect it to do. If you find any bugs, fix them and test your solution again. If you're unable to find any bugs, you can ask for help from your friends or the community.

7. **Optimize Your Code:** Once your code is working correctly, see if there's any way to make it more efficient. Can you reduce its time complexity? Can you use less memory? Even if your solution is already acceptable, optimizing your code is good practice and can make a big difference in more challenging problems. We will learn about time and memory complexity later.

8. **Submit Your Solution:** Once you're satisfied with your solution, you can submit it. Even if you're confident in your solution, be prepared for the possibility of it being rejected. If it is, don't be discouraged; use it as an opportunity to learn and improve.

Solve the problem using the above steps. Here is the code for the problem in C++:

```c++
#include<iostream> // header file for taking input output
using namespace std;

int main() {
  long long int n; cin >> n; // take the input

  while (n != 1) { // loop until n is equal to 1
    cout << n << ' ';
    if (n % 2 == 0) { // if n is even
      n = n / 2; // divide n by 2
    }
    else { // otherwise, if n is odd
      n = 3 * n + 1; // multiply n by 3 and add 1
    }
  }
  cout << 1 << '\n'; // end the output with printing 1
  return 0;
}

// we have used `long long int` instead of `int`, thats because
// inside the loop the number can grow enough big that an `int`
// variable can't store that
```

### The Ultimate Question: Why should I start Competitive Programming?

Well, I believe that the ultimate goal of my existence is to be happy. And I have learned from many well-established people that getting a great job or being famous or other common stereotypical goals won't make you happy as when you get used to those they become meaningless.

I think happiness is living your present with excitement.

That being said, now your main goal is to find something that will make you happy. There are lots of things you can do like being a musician or an artist etc. For me it was CP. I can lose myself in CP for hours and hours and still hold my excitement. A good contest is enough to make my day.

Man, I am not saying that you have to choose CP too. Find anything that suits you well, delve into that and maybe you will find peace.

Because I wanna spend my precious time on something so that in the end I can say with Heisenberg, "I did it for me. I liked it, I was good at it, and I was really... I was alive".

**So what kinda benefits you will get by doing CP?**

- Fun and excitement(tons of it).
- "Competitive programming builds the basics in you. You became so expert in coding anything that learning framework then becomes a very very easy task. Because when you learn to read the codes of hard or advanced algorithms, what can be more complex than those?

  CP programming makes you versatile, so you can move from any stack to another. But when you only learn a specific framework or stack, your knowledge gets bounded.

  You can compare learning any natural language with this. Let's say you want to learn German/English. You need to learn grammar first then you can write a paragraph. In coding, you can think of CP programming as grammar learning and frameworks as paragraph writing! When you know grammar you can write a paragraph on any topic.
  Even after a good or average (not the best) career in CP, you will find the database, distributed system, and machine learning topics very much understandable to you."- Raihat Zaman Neloy

- You will find Interview problems much much easier if you do CP. Problem-solving skill is required in interviews and CP is the best and most exciting way to learn problem-solving.
- "Competitive programming is recognized and supported by several multinational software and Internet companies, such as Google and Meta (Facebook). Several organizations host programming competitions on a regular basis." - Wikipedia
- Participating in contests will help you show off your skills and get you noticed by recruiters. This was the case for me.
- Big Tech companies like Google, Facebook, Amazon, etc. hire people through interviews where in technical interviews (one part of the whole interview process), problem-solving is the main thing they look for and they ask questions that are very similar to CP problems. So if you do CP you will have a great advantage in technical interviews.
- [and many more...](https://www.quora.com/What-have-you-gained-from-competitive-programming-Did-you-go-into-research-Did-it-help-you-in-any-aspect-as-a-software-engineer-Did-it-help-you-get-an-in-depth-knowledge-of-a-programming-language-Did-it-affect-your-problem-solving-skills)

Let's discuss something if you think CP is the thing that you wanna do.

Many of us set this goal like I wanna be red and continuously **looking at the goal** and not enjoying our **current** hard work. I am not red but I can guarantee myself that when I will be red I will be happy for a day or two and will get used to it. So what was my 4-5 years of hard work all about? Just a day of excitement? I don't believe in so. Wouldn't it be great if I could live those 4-5 years of my life with excitement? Well yes. This is what I am currently doing. I am living in the present, working hard and whether I become successful or not I will still be happy as I was **alive** throughout the whole process and lived my life to the fullest.

May you find that something that you have been looking for throughout your life!

### The Secret

Not everyone has the privilege to do the things that they enjoy doing. If you have that privilege, then it's really cool. But most people don't have that privilege. So "Instead of doing things you enjoy, learn to enjoy the things you do". And CP is one of the things that you can easily fall in love with.

### Seriously vs Sincerely

If you find yourself approaching things too seriously like it's no fun playing a game if you take it "too seriously". So if you want to have fun, you should switch to approaching things sincerely, like you are still gonna give it all, but you are gonna recognize that this is a game and you are gonna try and enjoy yourself while doing it. This philosophy also applies to CP. Watch [this](https://www.youtube.com/watch?v=FbSNfj2S6Pw) for more.

### What Progress is Really Like

Imagine that you have an ice cube sitting on the table in front of you.

The room is cold and you can see your breath. It is currently twenty-five degrees. Ever so slowly, the room begins to heat up.

Twenty-six degrees. <br>
Twenty-seven. <br>
Twenty-eight.

The ice cube is still sitting on the table in front of you.

Twenty-nine degrees. <br>
Thirty. <br>
Thirty-one.

Still, nothing has happened.

Then, thirty-two degrees. The ice begins to melt. A one-degree shift, seemingly no different from the temperature increases before it, has unlocked a huge change.

Breakthrough moments are often the result of many previous actions, which build up the potential required to unleash a major change. This pattern shows up everywhere. Cancer spends 80 percent of its life undetectable, then takes over the body in months. Bamboo can barely be seen for the first five years as it builds extensive root systems underground before exploding ninety feet into the air within six weeks.

Credit: The book Atomic Habit by James Clear

So don't get depressed after starting CP. It takes time to get your work reflected on your progress.

### Which language should I use for CP?

Most Competitive Programmers (more than 95%) use C++ mostly because it's quite faster than other languages and it has some great built-in libraries(Standard Template Library (STL)) to ease your life. There are also many [other reasons](https://www.quora.com/Why-do-competitive-programmers-prefer-to-use-C++-instead-of-Java-in-the-programming-contests) for using C++.

You can also use other languages too but for CP C++ is preferable. Languages are just tools and it doesn't take more than a few days to understand the basics of a language.

Note that you don't have to be a master in C++ to start your CP journey. If you know the basics i.e. variables, data types, operators, conditions, functions, and loops, then you are ready to start CP. You can learn them from [here](https://www.javatpoint.com/cpp-tutorial) or any of your favorite youtube channels (for example this [freeCodeCamp C++ Tutorial](https://youtu.be/vLnPwxZdW4Y) is also good).

### Where to write codes? What are the best IDEs?

IDEs are where you will write your codes. You can use Sublime Text, Codeblocks, VS Code, or any other IDE that you like.

I use Sublime Text and it's pretty good **for CP.**

#### Sublime Text Setup

1. **Setup:** Check [this video](https://www.youtube.com/watch?v=Zlx7gmt3lBU) to set up C++ in Sublime Text for Competitive Programming in **Windows, Mac and Linux.**
2. **Snippets:** Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Sublime%20Text%20Setup.md#snippets) to set up some snippets for Sublime Text.
3. **Shortcuts:** Check [this](https://kirankoduru.github.io/python/sublime-text-ninja.html) to find useful shortcuts.
4. [Extra] Useful Tools: Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Sublime%20Text%20Setup.md) to set up useful tools (although not needed normally, I also don't use these).

##### My Windows Build

My sublime build system for CP looks like this on Windows:

```c++
{
    "shell_cmd": "g++ -Wl,-stack=268435456 -std=c++17 \"${file}\" -o \"${file_path}/${file_base_name}\" && \"${file_path}/${file_base_name}\" < \"C:\\Sublime_Inout\\input.txt\" > \"C:\\Sublime_Inout\\output.txt\"",
    "file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
    "working_dir": "${file_path}",
    "selector":  "source.c++",
}
```

Here, change `C:\\Sublime_Inout\\input.txt\` by the exact path of your input file and change `C:\\Sublime_Inout\\output.txt\` by the exact path of your output file.
Check [this](https://www.youtube.com/watch?v=G4qyzclix10) to know how to get file paths on Windows.

##### My Mac Build

My sublime build system for CP looks like this on Mac:

```c++
{
	"shell_cmd": "g++-11 -Wl,-stack_size,0x20000000 -std=c++17 \"${file}\" -o \"${file_path}/${file_base_name}\" && \"${file_path}/${file_base_name}\"<~/Desktop/Codes/input.txt>~/Desktop/Codes/output.txt  && rm \"${file_path}/${file_base_name}\"",
	"file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
	"working_dir": "${file_path}",
	"selector": "source.c++",
}
```

Here, change `~/Desktop/Codes/input.txt` by the exact path of your input file and change `~/Desktop/Codes/output.txt` by the exact path of your output file.
Check [this](https://www.youtube.com/watch?v=gxU1wlBAsig) to know how to get file paths on Mac.

Make sure to install `g++-11` using `brew install gcc@11`. Run `g++-11 --version` to check if it is installed properly.

<br>

<details> <summary> Your sublime text should look something like this </summary>

![sublime_text](https://i.ibb.co/3MvXcZ3/image.png)

</details>

<br>

##### bits/stdc++.h file not found on Mac

In Mac, if you get `bits/stdc++.h file not found` error, check [this](https://shahjalalshohag.notion.site/How-to-Fix-bits-stdc-h-file-not-found-in-MacOS-aa9e384cc6014bdc93769e7d110c469d) out. This should fix the issue, if not, then contact me.

##### Infinite Loop

When you are running your code in sublime text, if you get an infinite loop, then you can press `Ctrl + C` or `Cmd + C` to terminate your program. Or you can use `Tools > Cancel Build`.

Sometimes, your infinite loop might print an enormous amount of data to the output file in an instant. So your computer might freeze and if nothing of the above works, then you can just open the task manager and terminate the sublime text process. If that doesn't work, then you can just restart your computer and delete the output file.

#### VS Code Setup

Check [this](https://medium.com/@chinmaykulkarni8/how-to-setup-visual-studio-code-for-c-c-java-python-competitive-programming-angular-22fdc9b1f4c6) to setup C, C++, Java, Python in Visual Studio Code for Competitive Programming.

Run the following code to test your sublime text setup:

```c++
#include <bits/stdc++.h>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;
    cout << a + b << endl;
    return 0;
}
```

### Useful Keyboard Shortcuts

Shortcuts for Windows / Mac are given side by side.

#### General

1. `Ctrl + S` / `Cmd + S`: Save - Saves the current file or document.
2. `Ctrl + Shift + S` / `Cmd + Shift + S`: Save As - Saves the current file with a different name or location.
3. `Ctrl + C` / `Cmd + C`: Copy - Copies the selected text or item.
4. `Ctrl + V` / `Cmd + V`: Paste - Pastes the copied or cut text or item.
5. `Ctrl + X` / `Cmd + X`: Cut - Cuts the selected text or item.
6. `Ctrl + Z` / `Cmd + Z`: Undo - Reverses the last action.
7. `Ctrl + Y` / `Cmd + Y`: Redo - Reverses the last undo action.
8. `Ctrl + F` / `Cmd + F`: Find - Opens a search bar to find text within the current document or page.
9. `Ctrl + A` / `Cmd + A`: Select All - Selects all text or items in the current document or window.
10. `Alt + Tab` / `Cmd + Tab`: Switch Application - Switches between open applications or windows.
11. `Ctrl + O` / `Cmd + O`: Open File - Opens a file for editing.
12. `Ctrl + N` / `Cmd + N`: New File - Creates a new file.

#### Sublime Text Specific

1. `Ctrl + P` / `Cmd + P`: Go to File - Allows you to search for a file in the current project.
2. `Ctrl + D` / `Cmd + D`: Multiple Selections - Selects the next occurrence of the current word or selection and allows you to edit them all at once!
3. `Ctrl + /` / `Cmd + /`: Toggle Comment - Comments out the selected code or text.
4. `Ctrl + F5` / `Cmd + B`: Build/Run - Builds or runs the current file.
5. `Ctrl + Shift + D` / `Cmd + Shift + D`: Duplicate - Duplicates the selected text or line.
6. `Ctrl + K + B` / `Cmd + K + B`: Toggle Sidebar - Shows or hides the sidebar.
7. `Ctrl + Shift + Up Arrow` / `Cmd + Shift + Up Arrow`: Move Line Up - Moves the current line or selection up by one line.
8. `Ctrl + Shift + Down Arrow` / `Cmd + Shift + Down Arrow`: Move Line Down - Moves the current line or selection down by one line.
9. `Ctrl + Shift + N` / `Cmd + Shift + N`: New file - Creates a new file.

Note that you can change the shortcuts in sublime text by going to `Preferences > Key Bindings`.

### What is a Contest?

A contest is a competition where you have to solve a set of problems within a given time limit. You will be given a set of problems and you have to solve as many problems as you can within the given time limit. You will be ranked based on the number of problems you solve and the time you take to solve them. The person who solves the most number of problems in the least amount of time wins the contest.

### Competitive Programming Platforms

CP Platforms are websites where you can participate in online contests.

The most famous CP platform is [Codeforces](https://codeforces.com/). Check [this](https://blog.codingblocks.com/2019/sites-and-tools-for-competitive-programming/) to know about more platforms.

I would suggest participating in online contests on [Codeforces](https://codeforces.com/), [AtCoder](https://atcoder.jp/), and [CodeChef](https://www.codechef.com/) in the beginning.

We will discuss more about contests later.

### Verdicts

Once you submit your code, you will get a verdict based on multiple criteria. The most common verdicts are:

- **Accepted (AC):** Your solution passed all test cases! Good job!
- **Wrong Answer (WA):** Your program gave an incorrect output for a specific test case. As a result, it wasn't executed on the remaining test set. Note that the test cases are hidden, so you won't be able to see the test case on which your program failed.
- **Compilation Error (CE):** Your code failed to compile, likely due to a syntactic error. Solve the error by testing your code locally. Make sure you've selected the correct compiler upon submission.
- **Runtime Error (RE):** A fault occurred during the execution of your program. This could be due to issues like accessing an out-of-bound array index, dividing by zero, and so on.
- **Time Limit Exceeded (TLE):** Your program took more time to run than the specified limit. Note that, the execution time is the maximum time taken by your program to run on any test case. So, if your program is taking too much time on a specific test case, then it will get a TLE verdict.
- **Memory Limit Exceeded (MLE):** Similar to TLE, your program used more memory than the allowed limit.
- **Presentation Error (PE):** Your program ran successfully, and the output is correct, but the _output format_ is incorrect. This is usually due to a missing space, newline, or an extra space or newline.

Note that your code first gets compiled and then gets executed. That's why you will get a CE verdict even before it gets executed.

### What to do if I don't know how to solve a problem?

Most problems have editorials/tutorials. The tutorial link is normally attached to the problem statement.

Also, **join this discord server to get help from general people**. Link: [Bangladesh CP Server](https://discord.gg/hDSMZATsrM)

### How to Read Problem Statements?

- Read the problem statement thoroughly. Try to understand what the problem is asking you to do.
- Identify the key information, constraints, and requirements.
- Break the problem down into smaller parts or subproblems.
- Pay attention to input-output limitations and samples provided in the statement.
- Analyze the sample test cases and try to understand the problem better.
- Check out the notes section of the problem statement. It may contain some useful information.
- Use pen and paper to draw stuff to better understand the problem.
- If you are still confused, try to read the problem statement again.

### How to practice a problem efficiently?

- First of all, **deeply** understand what the problem asks you to do.
- Then you should try to solve it by yourself.
- At first glance, it may look like you have no idea what that random alien-made problem is asking you to do. But take your time. Always try to solve the problem using brute force. After that try to make your solution more efficient.
- Ok, so still you have no idea how to solve the problem? Try to look at it from a whole new angle.
- "Keep trying while you have new ideas, then look up the editorial/tutorial after **15+ minutes of being completely stuck**." - Kamil Debowski
- To be more precise, if you think you are getting into the solution, then take more time and try to solve it. But if you have no clue on how to solve it, then what is the point of wasting your valuable time? It will only slow down your improvement process.
- After solving a problem by looking at the editorial/others' codes, **think about why your way of thinking was not correct, and what did you miss**. This is reallyyyy important.
- Time to implement the problem. Try not to use any unnecessary macros. Try to make it more readable. It will help you debug the solution.
- After that read the implementations of some skilled users (searching for some useful tricks or really nice implementations). **This part is really important which will significantly improve your skill.**
- If the problem uses a new idea/trick/algorithm which is a classic one i.e. it might be helpful in the future then try to write that down so that in the future you can easily access it.
- Now, let me ask you a question, what did you learn from this problem?

### Kidlin's Law

Kidlin's law: If you can write the problem down clearly then the matter is already half solved.

This is also the same here in CP. First, understand what the problem asks you to do. Then proceed to solve it. If you understand it correctly, then you are half done. So don't start solving without understanding what the problem demands.

### Number of Problems

"Stop obsessing over the number of hours spent or problems solved. These numbers don't mean shit because the variance is so high and it is very easy to spend a lot of time and solve a lot of problems without learning anything." - Tähvend Uustalu (CF: -is-this-fft).

So the main goal is **to learn new stuff** by solving problems.

### Machine Learning

It's all about feeding your brain more data and making it learn. CP is not like your exams where you will just read some stuff and spit them out in the exams. CP is to think. CP is to populate your brain with new techniques, new ways to solve problems. So it will take time to make your machine(brain) learn and to use it to solve new problems with a high success rate.

It's all about Machine Learning.

### ICPC and National Contests

International Collegiate Programming Contest (ICPC) is like the world cup of Programming. University students from around the world participate in it.
First, some Regional contests happen in every region and the top teams from each region qualify for the World Finals.

National Contests are a similar format contest but it is only for the students of a specific country. Around 5 to 10 National Contests are held in Bangladesh every year.

Format:

- This is a team contest. Each team consists of 3 members.
- One computer for each team.
- 5 hours long contest.
- 9-15 problems.

Learn more [here](https://www.quora.com/What-is-the-ACM-ICPC).

### FAQ

- [What is the key to CP?](https://codeforces.com/blog/entry/47516)
- [Regarding Interviews and Jobs](https://www.quora.com/How-has-competitive-programming-helped-you-get-a-job)
- [CP Or Development (Part 1)](https://www.geeksforgeeks.org/competitive-programming-vs-software-development-where-should-i-invest-my-time/)
- [CP or Development (Part 2)](https://www.quora.com/Which-is-better-to-invest-time-in-competitive-programming-algorithmic-programming-on-websites-like-CodeChef-or-TopCoder-vs-software-development-app-dev-web-dev-etc-Why)
- [CP or Development (Part 3)](https://medium.com/it-paragon/competitive-programming-vs-software-development-where-should-i-invest-my-time-619841d202f3)

### Books

Check [this](https://cses.fi/book/book.pdf) if you want. It contains everything.

### Important Notes

- **Exercise** (at least running) and drink more water. It will surprisingly boost your learning capability.
- **Getting AC is not the final goal, learning something new is the final goal**. Exactly, for this reason, people solve thousands of problems but can't get better. You need to solve harder problems than your current level so that you can learn something new by solving that problem.
- Also, after you solve a problem, try to do it more efficiently if possible, and look at others' solutions. This way you will learn better and become better faster in the long run. Make sure that you truly _understand_ and _feel_ the solution.
- After solving a problem, **think about why your way of thinking was not optimal**. This is important too.
- **Design before you code.** Think about the solution/algorithm first, then code it. It will save you a lot of time.
- **SOLVE MORE PROBLEMS**.
- Talk to similar-minded people. Make friends who are also interested in CP. It will help you a lot.
- Always ask `Why?`.
  - Why is this solution not correct?
  - Why is this solution correct?
  - Why is this solution optimal?
  - Why is this solution not optimal?
  - Why did this solution get TLE?
  - Why did this work?
  - Why do we exist...?

### Tutorial

- [The Ultimate Topic List](https://youkn0wwho.academy/topic-list)

Check the above link. You will find everything categorized there. Then check the [guideline](https://youkn0wwho.academy/topic-list/guideline) page.

So basically start with the basics section. Complete the topics under this section, you will find resources and problems for everything in increasing order of completion.

After you are done with the basics section, select a difficulty and importance (3\* topics first), then complete them one by one.

Meanwhile, always participate in live contests and solve some random problems from time to time.

Also, you can sometimes try to do rating-wise practice. And make sure that you are not solving too many easy problems. Try to solve problems that are a bit harder than your current level.

_Do not get overwhelmed by the number of topics. Just start with the basics and keep going. If you are done with the basics, then you are already better than 80% of the people and ready to be an Expert in Codeforces. And, if you are done with the 3\* topics of easy and medium difficulty, then you can be a Grandmaster in Codeforces once you solve enough problems._

---

### Life Hack(if you are from Bangladesh)

If you want a complete guideline like this for EVERYTHING about CP and you are from Bangladesh, then you can check out my academy and enroll in some courses that fits you well.

Link: [YouKn0wWho Academy](https://academy.shahjalalshohag.com/).

---

### Code Library

- [Almost all the important templates that you will need in CP](https://github.com/ShahjalalShohag/code-library)

### Common Mistakes

Check out [[Tutorial] Common Mistakes in Competitive Programming and How to Avoid Them](https://codeforces.com/blog/entry/111217)

### How to Debug

Debugging is the process of finding and fixing bugs (errors) in your code. It's a very important skill that you need to master.

- **Understand Error Messages:** Read the error messages carefully and try to understand what they mean.
  For example, if you see a message like this:

  ```c++
  my_program.cpp: In function ‘int main()’:
  my_program.cpp:4:12: error: ‘x’ was not declared in this scope
  ```

  This tells you that on line 4 of `my_program.cpp`, you're trying to use a variable x that the compiler doesn't know about.

- **Print and Check:** This is the best way to debug your code. Print the values of variables and check if they are what you expect them to be.
  For example, consider calculating the factorial of a number $n$ where $n$ could be up to $20$. Here's a buggy code:

  ```c++
    #include <bits/stdc++.h>
    using namespace std;

    int main() {
      int n;
      cin >> n;
      int fact = 1;
      for (int i = 1; i <= n; i++) {
        fac *= i;
      }
      cout << fact << '\n';
      return 0;
    }
  ```

  If you run this, you will get a compilation error because `fac` is not defined. But if you fix that, you will get a wrong answer. So, you need to print the value of `fac` in each iteration to see what's going wrong.

  ```c++
    #include <bits/stdc++.h>
    using namespace std;

    int main() {
      int n;
      cin >> n; // input n = 20
      int fact = 1;
      for (int i = 1; i <= n; i++) {
        fact *= i;
        cout << fact << '\n';
      }
      cout << fact << '\n';
      return 0;
    }
  ```

  Now, you can see that some of the values of `fact` become negative after $12!$. Why? Because the maximum value that an `int` can store is $2^{31}-1$ which is less than $13!$. So, you need to use a `long long` instead of an `int`.

  ```c++
    #include <bits/stdc++.h>
    using namespace std;

    int main() {
      int n;
      cin >> n; // input n = 20
      long long fact = 1;
      for (int i = 1; i <= n; i++) {
        fact *= i;
      }
      cout << fact << '\n';
      return 0;
    }
  ```

### Stress Testing

- [Find a counter-test](https://ali-ibrahim137.github.io/competitive/programming/2020/08/23/Stress-Testing.html)

### Coding Style

**IMPROVE YOUR CODING STYLE. IT DESCRIBES YOURSELF!**

- It's important because it makes your code more readable and understandable.
- It's important because it makes your code more beautiful.
- It's important because it helps you to debug your code easily.
- It's important because it helps your teammates to understand your code easily.
- It's important because it will help you during interviews.
- It's important because if you don't follow a coding style in your job, you might get fired!

<br>

Tutorial: [link](https://codeforces.com/blog/entry/64218).

**Online formatter:** [link](https://codebeautify.org/cpp-formatter-beautifier), you can use this to check how your ugly codes can be made beautiful.

<br>In short:

- Use proper indentations and spacings.
- Use `const` if you are using the same value multiple times. For example, `const int N = 1e5 + 9` or `const int INF = 1e9 + 9`.
- Use not more than three macros(for example, `#define ll long long` is acceptable).
- After any condition, loop, or function, write the curly bracket on the same line, not on the next line.
- Write variables on the go. `for (int i = 1; i <= n; i++)`. Here `i` has been declared on the go.
- Use meaningful variable/function names.
- Naming Conventions: `snake_case` or `camelCase` for variables and functions, `PascalCase` for classes and structures. I personally use `snake_case` for variables and functions.
  - `snake_case`: Words are separated by underscores. For example, `int max_value_possible = 0`.
  - `camelCase`: Words are separated by capital letters, but the first word starts with a small letter. For example, `int maxValuePossible = 0`.
  - `PascalCase`: Words are separated by capital letters, and the first word also starts with a capital letter. For example, `struct MaxValuePossible {}`.
- Comment your code. It helps you to understand your code later.
- Consistency is the key. If you are using `snake_case` for variables, then use it everywhere. Don't use `snake_case` for some variables and `camelCase` for others.

<br>You can follow other users on Codeforces and make them friends (click the star button on the right of the username on CF) and check their solutions using the "friends only" button. I like the coding styles of the following users:

- [neal](https://codeforces.com/profile/neal)
- [YouKn0wWho](https://codeforces.com/profile/YouKn0wWho)
- [mango_lassi](https://codeforces.com/profile/mango_lassi)
- [jiangly](https://codeforces.com/profile/jiangly)
- [tourist](https://codeforces.com/profile/tourist)
- [Anachor](https://codeforces.com/profile/Anachor)
- [Bruteforceman](https://codeforces.com/profile/Bruteforceman)
- [Others](https://codeforces.com/blog/entry/77865)

### More About Contests

#### Codeforces

Website: [https://codeforces.com/](https://codeforces.com/)

- **How to Use Codeforces**
  - Check this guide: [must check](https://codeforces.com/blog/entry/99660).
- **How do Codeforces' contests work?**
  - Read this: [must check](https://codeforces.com/blog/entry/456).
- **Problem Rating**
  - Each problem has a rating that indicates contestants with which average rating solved this problem previously. Check [this](https://codeforces.com/blog/entry/62865) to know more about this and **how to sort problems based on ratings.**
- **Problem Tags**
  - Each problem has some tags that indicate the topics related to the problem. Check [this](https://codeforces.com/blog/entry/14565) to know more about this.
- **Make Sure You Know the Following:**
  - How to submit a solution.
  - How to see other's solutions.
  - How to see the test cases.
  - How to see the standings.
  - How to see the editorial.
  - How to see the discussions.
  - How to sort problems based on ratings.
  - How to up-solve problems.
  - What are different divisions and how to participate in them.

#### AtCoder

Website: [https://atcoder.jp/](https://atcoder.jp/)

The process is similar to Codeforces.

#### CodeChef

Website: [https://www.codechef.com/](https://www.codechef.com/)

The process is similar to Codeforces.

#### Should I Participate in Contests?

Some people think that they will learn some topics first and once they are done with learning, they will participate in contests. But this is a veryyyy bad practice.

**YOU SHOULD PARTICIPATE IN ALL CONTESTS.**

Participating in contests in real-time, trying to solve problems in a limited amount of time, competing with thousands of people all over the world, not being able to solve during the contest, up-solving after the contest, reading editorials, reading other's solutions, reading discussions, etc. will help you a lot in learning new things and improving your skills.

I will **strongly** recommend you participate in the following contests:

- Codeforces Div. 4, Div. 3, and Div. 2 contests.
- AtCoder Beginner Contests.
- CodeChef Starters Contests.

### Virtual Contests

Virtual contests will give you a real-time experience. It enables the users to run past contests in a special mode that would imitate real competition. It feels just like a real contest with real contestants competing alongside the participant who writes a virtual contest. But it won't affect your rating.

For Codeforces, click on `Virtual participation` on the [contest page](https://codeforces.com/contests) to participate in a virtual contest. You can pick your own start time for the virtual contest.

### Useful Tools

- [Chrome/Firefox Extension to analyze Codeforces profiles](https://codeforces.com/blog/entry/93417)
- [Codeforces Practice Tracker — Browser Extension](https://codeforces.com/blog/entry/78203)
- [CF-Predictor](https://chrome.google.com/webstore/detail/cf-predictor/ocfloejijfhhkkdmheodbaanephbnfhn)
- [Codeforces Live Bot (Telegram Bot)](https://codeforces.com/blog/entry/82669)
- [Codeforces Visualizer](https://cfviz.netlify.app/)

Get familiar with problem-solving by solving these problems. You won't need to know anything other than the basics of a language to solve them.

**Hint:** [How to Practice?](https://github.com/ShahjalalShohag/Competitive-Programming-A-Complete-Guideline#how-to-practice-a-problem-efficiently) <br>

**REMEMBER THAT SOLVING MORE PROBLEMS IS THE KEY**

### Similar Tutorials

- [A way to Practice Competitive Programming : From Rating 1000 to 2400+ by Masataka Yoneda](https://drive.google.com/file/d/1J2x8pIYQ3MXANgvzOgBciWd3d79j_Exa/view)
- [From Beginner to Grandmaster - Complete Roadmap for Competitive Programming by Galen Colin](https://www.youtube.com/watch?v=bSdp2WeyuJY)

Also, remember to exercise and drink more water. It helps a lot.

Good luck <a href="https://emoji.gg/emoji/8771_blobheart"><img src="https://emoji.gg/assets/emoji/8771_blobheart.png" width="16px" height="16px" alt="blobheart"></a>.
