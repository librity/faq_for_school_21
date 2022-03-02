## 42 School FAQ for beginners and plebs

This article is intended for those who are new to 42's community and methodology.
It's also a reminder for older students who forgot the basics and want to avoid
toxic slack questions that will make them look foolish to more experienced cadets.

I urge all newcomers to read [nohello.com](https://www.nohello.com/) before asking their first question on Slack.
Learn to ask questions like this:

> Hello, how you doing? I have a PROBLEM in my PROJECT_NAME project. I can't figure out what's wrong. I tried googling SEARCH_REQUEST and SEARCH_REQUEST, I read LINK and LINK, but I didn’t quite understand what QUOTE means for this LINK: after all, man FUNCTION says X, I have X, but for some reason it doesn’t work ... I walked through the debugger, it turns out that on line N the variable VAR becomes VALUE for me, although I expected ANOTHER_VALUE there. Where do you think ANOTHER_VALUE came from?
> CODE_SNIPPET, SYSTEM_NAME system.

For questions, inconsistencies and errors, you can drop me a line on slack. My nickname is `swarner`.
For everything else, ask your school's administrative team (ADM, Bocal, etc.)

## Index

**Non-technical questions**

- [Remote Evaluations](#remote_evaluations)
- [Grading Accidents](#grading_accidents)
- [Tig Questions](#tig)
- [Slack is deleting old messages!](#slack_panic)
- [How do I bring a guest to school?](#guests)
- [What do I do if I get sick?](#sick)
- [Pedagogical and Community Meetings](#meetings)
- [School Certificate and Degree](#certificate)
- [Intra's Black Hole](#blackhole)
- [Buying physical objects with Altarians (₳)](#altarians)
- [The 42 Norm](#norm)
- [Exam Questions (C Exam Alone In The Dark - Beginner)](#exam)
- [How to get a license for JetBrains (Clion, PyCharm, etc.)](#get_jetbrains)
- [It's time to make a summary. Where to start?](#cv)
- [Sites with level counter for projects](#top_21)
- [Useful channels in slack](#slack)
- [Information about peers](#find-peer)

**Technical questions**

- [Coding WIKI](#coding_wiki)
- [GCC or Clang?](#compiler)
- [How to check remaining space on school mac?](#mac_memory)
- [Error while cloning repository (Permission denied (publickey))](#error_publickey)
- [I set up norminette according to the official guide, but it still doesn't work.](#vpn_norminett)
- [Installing Oh-My-Zsh](#zsh)
- [Install HomeBrew on Mac](#brew)
- [Likbez on computer memory device and leaks](#memory_manual)
- [Installing valgrind to find leaks](#valgrind)
- [Check for leaks in a graphic project (FDF, Fract'ol and others)](#gui_leaks)
- [Leaks: error "Failed to gain authorization"](#leaks_auth_error)
- [Ran out of space on the poppy. How to clear the cache?](#cache)
- [Why did moulinette set -42 in fillit for a function from libft](#error_fillit)
- [Configuring debugger in vscode](#vscode)
- [Setting clion](#clion)
- [Configuring Xcode to work with School 21 projects](https://dimaru.github.io/guides-21/Xcode_setup.html)
- [Creating a project in Xcode](https://dimaru.github.io/guides-21/Xcode_21.html)
- [norminette for Xcode](https://github.com/DimaRU/NorminetteLint)
- [Plugin for Xcode Header 42](https://github.com/DimaRU/School42Header)
- [Collection of checkers for projects](#checkers)

## Non-technical questions

## <a name="remote_evaluations">Remote Evaluations</a>

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="grading_accidents">Grading Accidents</a>

Remember!
If you accidentally flunk a project as an evaluator (missclick or otherwise),
the evaluatee will have to resubmit the project and evaluate it all over again.
The school's administrative team won't correct correct or reset closed evaluations.
Be very careful and thorough with grading or you might ruin someone's day,
and waste everyone's time and effort!

## <a name="tig">TIG questions</a>

#### What is a TIG?

_Travail d'Intérêt Général_ in French, or General Interest Work,
TIGs are punitive measures enforced by the school's administrative team.
They usually involve helping other students with their projects
for a fixed amount of time.

#### I was given a 2/4/8 hour TIG. What does that mean?

The duration of the TIG depends on the severity of misconduct.
If you are given an 8-hour TIG you can usually spread it out over multiple days.

#### I got a TIG, what should I do?

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

#### I was absent at a TIG training, now what?

If you miss a TIG training the administration will automatically give you a second two-hour TIG.

#### I want/need to reschedule a TIG. What do I do?

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="slack_panic">Slack is deleting old messages!</a>

We all know that Slack deletes old messages from time to time.
In order for all history to be preserved, the school would have to pay an absurd
amount of money Slack (~$100,000) given the large number of people that use the server.

Some schools use alternative services like Discord.
Check with your school's administration and use whatever service they recommend.

## <a name="guests">How do I bring a guest to school?</a>

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="sick">What do I do if I get sick?</a>

If you are sick, it's better to stay at home to avoid spreading it to other students.
You don't need to inform the administration.
However, if you will miss deadlines due to your sickness,
check with your school's administration for possible extensions.
We're talking about serious illnesses here, not just a runny nose.

## <a name="meetings">Pedagogical and Community Meetings</a>

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="certificate">School Certificate and Degree</a>

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="blackhole">Intra's Black Hole</a>

Schools around the world have different progression mechanisms,
and not all of them use the Black Hole system.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="altarians">Buying physical objects with Altarians (₳)</a>

Varies from school to school.
Check with your school's administrative team (ADM, Bocal, etc.)

## <a name="norm">The 42 Norm</a>

#### Where can I find the latest version?

The latest version (`3.x.x`) of both the norm and norminette checker
can be found in the official repo:

- https://github.com/42School/norminette
- https://github.com/42School/norminette/tree/master/pdf

It has English, French, Japanese, Korean, Portuguese and Turkish translations.

#### Can I use C Function-Like Macros?

Function-like macro are forbidden by the norm:

> #define SUM(x, y) (x + y)

Besides, there is absolutely no need for such things. Just create a separate function.

#### Can I use static or global variables?

Static variables can be used without restrictions.
Global variables are allowed, but their use must be justified.
Some projects flat-out forbid the use of global variables,
so beware of that.

```diff
Global Variables:
- Unreasonable use: a variable used in a single function.
+ Reasonable use: A pointer to a shared storage structure.
```

#### Can I use constants from `limits.h` or `bool.h` headers?

You are allowed to use constant defines from system headers
as long as you're not also using forbidden functions.

#### How do I comment my code?

Comments aren't allowed inside the function's body.
C99-style comments (`//`), are not allowed.
A well-formed comment looks like this:

> /_  
>  \*\* YOUR COMMENT HERE.  
>  _/

## <a name="exam">Exam Questions (C Exam Alone In The Dark - Beginner)</a>

#### What time and what time are the exams?

Thursdays at 12:00. If by next Saturday there are volunteers who are ready to look after the examinees, then it will be this Saturday at 12:00.

#### How to log in to the exam correctly?

- We come and log in using the exam account - exam:exam.
- Next, go to the terminal and write kinit [your login] and enter your password.
- We are waiting for the command from the examiners about the beginning of the exam and then write examshell in the terminal.
- The exam has begun!

#### Do I need to bring to the norm in the exam?

No. This is not required for the exam.

#### I did everything right, tested it, and moulinette returned 0!!!

So something is wrong. Carefully read the traceback from moulinette (knowledge of the diff command will help a lot). It is also likely that you forgot to compile with the -Wall -Werror -Wextra flags and did not see the hidden error. However, moulinette is a software package, and it can also have errors. If you think that this is your case, you can try to dispute it in ADM.

#### On the exam I did everything up to level 3. What level can I start next time?

In fact, if you made levels 00-03 inclusive, then left, then upon arrival you can start from any level to which you have reached and the maximum points will be offered, and not how many you have scored. That is, if you made levels 00-03, for example, by 16-11-16-16 points, then you left the next time you can start from level 00-04, and for 04 you will immediately be prompted for 80 (16-16-16 -16-16).
Plus there is an exception with level 5, if you did 04 without an error and left, then next time you can start from 05 already for 100 points, but if you did 04 with an error, then you will not be able to start from 05 next time if left, and again from 04 for 80 points

## <a name="get_jetbrains">How to get a JetBrains (Clion, PyCharm, etc.) license</a>

1. Go to the [JetBrains](https://account.jetbrains.com/login) website and create an account.
2. Next, follow the link [Apply for a free student or teacher license for educational purposes]
3. Click "Apply now".
4. Enter correctly all your data in the form. Email must indicate your school - [your nickname]@student.21-school.ru.
5. Wait for confirmation by mail.

## <a name="cv">It's time for a resume. Where to start?</a>

- Read [recommendations for writing a resume](docs/Rekomendatsii_po_napisaniyu_rezyume_Scheglova_L.docx)
- Go to [canva.com](https://www.canva.com/) and start creating your resume :)

<a name="top_21">Sites with a level counter for projects</a>

---

- [https://isthisjazz.website/xpcalc.php](https://isthisjazz.website/xpcalc.php)
- [https://42.tbailleu.dev/](https://42.tbailleu.dev/) - current

## <a name="slack">Useful channels in slack</a>

- #chess_school21 - chess club.
- #schoolcoffee - once a week we meet a new person and drink coffee.
- #mafia - mafia in the Moscow campus.
- #21hackers - channel with hackathons.
- #21lectures - studentnts write who they want to invite to the school as a lecturer.
- #it_news - news from the IT world, meetups, webinars, hackathons.
- #born_to_code - a channel for questions about projects and code.
- #lab_moscow - robotics channel in Moscow.
- #lab_kazan - robotics channel in Kazan.
- #lab_news - news from the world of electronics and robotics.
- #coding_cups - programming contests.
- #help - channel for cleaning help.
- #kvartira - search for housing.
- #talks - discussion of pressing issues of the school with the principal.
- #dir_talks -||-
- #datascience - Scientist data channel.
- #web - channel of web developers.
- #school_life - an overview of events and channels.
- #java - mostly Java SE.

## <a name="find-peer">Peer Information</a>

- Telegram bot [@peer_location_bot](https://t.me/peer_location_bot)
- Campus based school coffee [@randomcoffeefrybot](https://t.me/randomcoffeefrybot)
- Rating of students by level [jcorwin.ru](https://jcorwin.ru/)

## Technical questions

## <a name="coding_wiki">Coding WIKI</a>

A very useful notion page that contains a lot of useful educational information (lectures/guides/instructions/reminders).
Link - [Coding WIKI](https://www.notion.so/coding_wiki-1d8b8bc675f5426db90a02dd22324ac8)

## <a name="compiler">GCC or Clang?</a>

Do not forget that Clang is used at our school, not GCC (an alias is made).
There are strong differences between them (in particular, GCC is stricter with -Werror -Wall -Wextra).
So, when working on our system, we compile using Clang.

## <a name="mac_memory">How do I check the remaining space on my school mac?</a>

Learn to use standard terminal commands.

> mandu
> man df

## <a name="error_publickey">Error while cloning repository (Permission denied (publickey))</a>

Do not forget to follow the steps from [21-school.ru/ssh](http://21-school.ru/ssh):

1.ssh_keygen 2. Enter three times 3. cat ~/.ssh/id_rsa.pub 4. Insert the entire contents of the file into the intra using the link [https://profile.intra.42.fr/gitlab_users/new](https://profile.intra.42.fr/gitlab_users/new) 5. School VPN must be enabled.

All the necessary instructions are available at [21-school.ru/adm](https://21-school.ru/adm).

## If the problem persists after all the above actions, then we first turn to the students in the slack or left / right. If they do not help, we write in a glass about the problem.

## <a name="vpn_norminett">I set up norminette according to the official guide, but it still doesn't work.</a>

Check if the school's DNS server settings are recorded.
DNS - 192.168.50.130
Domains msk.21-school.ru

For example, on linux, the /etc/resolv.conf file will contain the following lines:

> nameserver 192.168.50.130
> search msk.21-school.ru

School IP to check:
IP vogsphere:

> 192.168.50.135

IP norminette:

> 192.168.50.133

## <a name="zsh">Install Oh-My-Zsh</a>

We write to the terminal and run:

> sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

## <a name="brew">Installing HomeBrew on a Mac</a>

We write to the terminal and run:

> curl -fsSL https://rawgit.com/kube/42homebrew/master/install.sh | zsh

## <a name="memory_manual">Learning about computer memory and leaks</a>

This educational program was written by a student of school 21 **amatilda**.
It answers the most common questions about memory and memory leaks.
Beginning programmers and new students of school 21 are highly recommended for reading and studying.
The manual can be found - [HERE](docs/memory_leaks_amatilda.pdf)

## <a name="valgrind">Installing valgrind to find leaks</a>

We write to the terminal and run:

- Install HomeBrew:

  > curl -fsSL https://rawgit.com/kube/42homebrew/master/install.sh | zsh

- Connect the repository:

  > brew tap LouisBrunner/valgrind

- Install valgrind:
  > brew install --HEAD LouisBrunner/valgrind/valgrind

Usage:

> valgrind ./[your binary] [args] --leak-check=full

## <a name="gui_leaks">Checking for leaks in a graphic project (FDF, Fract'ol and others)</a>

There are two ways to check for leaks in graphics projects.
First:

1. Run your program
2. In another terminal, write:
   > leaks [name of your binary]

Second:

1. Launch Xcode
2. At the top, click on the Xcode tab
3. Search for "Open Developer Tool" and click on "Instruments"
4. Choose "Leaks"
5. Click on the button with a red circle and select your binary.
6. If you need arguments, write them in the "Arguments" field.

## <a name="leaks_auth_error">Leaks: "Failed to gain authorization" error</a>

If you get a "Failed to gain authorization" error when trying to run the Leaks tool:

1. Create an entitlement file using the com.apple.security.get-task-allow entitlement:
   > % /usr/libexec/PlistBuddy -c "Add :com.apple.security.get-task-allow bool true" tmp.entitlements<br/>
   > File Doesn't Exist, Will Create: tmp.entitlements
2. Sign your code with these rights:
   > % codesign -s - --entitlements tmp.entitlements -f /path/to/tool<br/>
   > xxst: replacing existing signature

After that Leaks will run your program successfully.<br/>
Solution found on the Apple Developer forum (link to <a href="https://developer.apple.com/forums/thread/685964">thread</a>)

## <a name="cache">Ran out of space on Mac. How to clear the cache? Enter the commands in turn.</a>

> rm -rf ~/Library/Caches/\*

> rm -rf ~/Library/_42_cache_

> rm -rf ~/Library/Application\ Support/Slack/Service\ Worker/CacheStorage/

> rm -rf ~/Library/Application\Support/Slack/Cache/

> rm -rf ~/Library/Application\ Support/Slack/Code\ Cache/

## <a name="error_fillit">Why did moulinette put -42 in fillit for a libft function</a>

This happens because moulinett in the fillit project doesn't properly handle headers that are built like this:

> #include "../libft/libft.h"

It is necessary to fix all headers in the project to:

> #include "libft.h"

And also copy the libft.h file itself to the includes folder in the project root.
And fix the Makefile in the place where the headers are connected to:

> -I includes/

On all other projects, there is no difference how to connect headers. This issue has only been seen in fillit.

## <a name="vscode">Setting up a debugger in VSCode</a>

- Install the [CodeLLDB] extension in VSCode(https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)
- Don't forget to read the Users Manual, there's a lot of interesting stuff in there.

Or:

- We take and copy the configuration from [this file] (docs/launch.json)
- Insert everything instead of your launch.json file, which is in .vscode
- After you will see the button "(lldb) Run" at the top
- Now you can debug your code :)

You can change the ${workspaceFolderBasename} variable to the name of your binary if your binary is not named the same as the folder.
To run the program with arguments, you need to insert your arguments in brackets in the line - "args": [], in brackets.

## <a name="clion">Configuring Clion</a>

For correct operation of clion, you need an analogue of Makefile - CMakeList.txt. Fortunately, clion can generate it automatically.

1. You need to open clion and click - New CMake Project from sources.
2. A window will open where you will need to select a project folder.
3. Click OK in the next window, where clion offers to select project files.
4. Clion is ready to go.

If you need to run a program with arguments:

1. Click on the Run tab at the top.
2. We are looking for Edit configurations and click.
3. Enter the arguments in the Program arguments field.

## <a name="checkers">Collection of project checkers</a>

Checker for 6 initial projects -
[42FileChecker](https://github.com/jgigault/42FileChecker)

####libft

[libft-unit-test](https://github.com/alelievr/libft-unit-test)
[libftest](https://github.com/jtoty/libftest)
[test-libft](https://github.com/saugustu42/test-libft)

#### Fillit

[fillit_checker](https://github.com/Millon15/fillit_checker)

#### Ft_printf

[pft](https://github.com/gavinfielder/pft)
[printf-unit-test - 3.4 million tests](https://github.com/alelievr/printf-unit-test)
[curqui_test](https://github.com/curquiza/curqui_test)

#### Push_swap

[push_swap checker](https://github.com/ksnow-be/push_swap_checker) (super cool checker made by student of school 21)
[Push_swap Visualization](https://github.com/elijahkash/push_swap_gui)

#### Lem-in

[Lem-in-Checker](https://github.com/emilwallner/Lem-in-Checker)
[lem-in_test](https://github.com/TBouder/lem-in_test)

#### Filler

[filler_checker](https://github.com/Millon15/filler_checker)

### corewar

[42-Corewar-Checker](https://github.com/Gliperal/42-Corewar-Checker)
[unit-tests](https://github.com/rizkyario/corewar/tree/unit-tests)