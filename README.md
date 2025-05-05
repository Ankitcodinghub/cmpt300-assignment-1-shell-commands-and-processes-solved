# cmpt300-assignment-1-shell-commands-and-processes-solved
**TO GET THIS SOLUTION VISIT:** [CMPT300 Assignment 1-Shell Commands and Processes Solved](https://www.ankitcodinghub.com/product/cmpt300-assignment-1-shell-commands-and-processes-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95223&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT300 Assignment 1-Shell Commands and Processes Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

1. Overview

In this assignment, you will develop a simple Linux shell. The shell accepts user commands and then executes each command in a separate process. The shell provides the user a prompt at which the next command is entered. One technique for implementing a shell interface is to have the parent process rst read what the user enters on the command line and then create a separate child process that performs the command. Unless otherwise specied, the parent process waits for the child to exit before continuing. However, UNIX shells typically also allow the child process to run in the background – or concurrently – as well by specifying the ampersand (&amp;) at the end of the command. The separate child process is created using the fork() system call and the user’s command is executed by using one of the system calls in the exec() family.

Note: As usual, all code must be written in C and run on a Linux machine. We will grade your code on a Linux machine. You should create a directory for this assignment, such as ~/cmpt300/a1/ and put all les related to this assignment in it.

2. A Simple Shell

A C program that provides the basic operation of a command line shell is given below. The main() function rst calls read_command(), which reads a full command from the user and tokenizes it into separate words (arguments). These tokens can be passed directly to execvp() in the child process. If the user enters an “&amp;” as the nal argument, read_command() will set the in_background parameter to true (and remove the “&amp;” from the array of tokens). For example, if the user enters “ls -l” at the ‘$’ prompt, tokens[0] will contain “ls”, tokens[1] will contain (or point to) the string “-l”, and tokens[2] will be a NULL pointer indicating the end of the arguments. (Each of these strings is a NULL terminated C-style string). Note that the character array buff will contain the text that the user entered; however, it will not be one single NULL terminated string but rather a bunch of NULL terminated strings, each of which is a token pointed to by the tokens array.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
#include &lt;stdio.h&gt; #include &lt;stdbool.h&gt; #include &lt;stdlib.h&gt; #include &lt;string.h&gt; #include &lt;unistd.h&gt;

#define COMMAND_LENGTH 1024

#define NUM_TOKENS (COMMAND_LENGTH / 2 + 1)

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
<div class="column">
1/8

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
2021/2/2 SFU CMPT 300 – Assignment 1

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
<pre>/**
 * Read a command from the keyboard into the buffer 'buff' and tokenize
</pre>
<pre>it
 * such that 'tokens[i]' points into 'buff' to the i'th token in the
</pre>
<pre>command.
 * buff: Buffer allocated by the calling code. Must be at least
 *       COMMAND_LENGTH bytes long.
 * tokens[]: Array of character pointers which point into 'buff'. Must be
</pre>
at

<ul>
<li>
<pre> * &nbsp;      least NUM_TOKENS long. Will strip out up to one final '&amp;' token.
</pre>
</li>
<li>
<pre> * &nbsp;      'tokens' will be NULL terminated.
 * in_background: pointer to a boolean variable. Set to true if user
</pre>
entered
</li>
</ul>
<pre> *       an &amp; as their last token; otherwise set to false.
 */
</pre>
void read_command(char *buff, char *tokens[], _Bool *in_background) {

<pre>        // ... Full code available in shell.c...
</pre>
}

<pre>/**
 * Main and Execute Commands
 */
</pre>
int main(int argc, char* argv[]) {

char input_buffer[COMMAND_LENGTH]; char *tokens[NUM_TOKENS];

while (true) {

</div>
</div>
<div class="layoutArea">
<div class="column">
work with

</div>
<div class="column">
<pre>// Get command
// Use write because we need to use read()/write() to
</pre>
<pre>// signals, and they are incompatible with printf().
</pre>
write(STDOUT_FILENO, “$ “, strlen(“$ “));

_Bool in_background = false; read_command(input_buffer, tokens, &amp;in_background);

<pre>/**
 * Steps For Basic Shell:
 * 1. Fork a child process
 * 2. Child process invokes execvp() using results in
</pre>
<pre> * 3. If in_background is false, parent waits for
</pre>
<ul>
<li>
<pre> * &nbsp;   child to finish. Otherwise, parent loops back to
</pre>
</li>
<li>
<pre> * &nbsp;   read_command() again immediately.
 */
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
token array.

</div>
</div>
<div class="layoutArea">
<div class="column">
}

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
3. Problems

There are three mandatory problems (100 points) that you will need to solve:

Create the child process and executing the command in the child. Implement some internal commands.

Implement a history feature.

There is also one optional problem for a 20-point bonus, but you must attempt the mandatory problems rst, before attempting the bonus problem. Attempting the bonus problem without work done in the mandatory problems will not get you any points for the bonus problem.

Problem 1. Creating Child Process

First, modify main() so that upon returning form read_command(), a child is forked and executes the command specied by the user. As noted above, read_command() loads the contents of the tokens array with the command specied by the user. This tokens array will be passed to the execvp() function, which has the following interface:

where command represents the command to be performed and params stores the parameters to this command. For this project, the execvp() function should be invoked as

Be sure to check the value of in_background to determine if the parent process is to wait for the child exit or not. Hint: use waitpid() instead of wait() because you want to wait on the child you just launched. If you only use wait() and have previously launched any child processes in the background that have terminated, wait() will immediately return having “consumed” the previous zombie process, and your current process incorrectly acts as though it was run in the background. Note that we won’t be testing with interactive command-line processes run in the background (think vim), or test using signals while running a command in the background. If execvp() returns an error (see man execvp) then display an error message. Note that using printf() may not work well for this assignment and that you should use write() instead (look up more with man write). The issue is that we need to use the read() function for getting the user’s command and use write() when working with signals (later). And, it turns out that printf() and read()/write() don’t always work well together. Therefore, when printing to the screen, use the write() command. For common things, such as displaying a simple string, or writing a number to the screen, you may want to make your own functions which make it easier. You can convert an integer to a string using sprintf().

Waiting Aside: When a process in Linux nishes, it still exists in the kernel with some status information until the parent process waits on that child. These un-waited-on terminated child processes are known zombies. For this assignment, you won’t lose any marks if you don’t correctly

</div>
</div>
<div class="layoutArea">
<div class="column">
execvp(char *command, char * params[]);

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>execvp(tokens[0], tokens);
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
}

</div>
</div>
<div class="layoutArea">
<div class="column">
return 0;

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
wait() on zombie processes from background tasks; however, it’s a good habit to correctly cleanup the zombies on your system! Above it is suggested that you use waitpid() to wait on the correct child. However, this will leave any background process as zombie processes (having exited, the parent process will never wait() on the child). You can correct this by occasionally trying a non- blocking wait to handle any zombie child processes. We can pass the WNOHANG option to waitpid() to be non-blocking, and setting the PID to -1 will wait on any child process. For example, have the following code run after every user command is processed:

Problem 2. Shell Prompt and Internal Commands

First, make sure your shell prompt always shows the current working directory. For example, if in the

/home/cmpt300 folder, the prompt should be:

Next, let’s implement some internal commands. Internal commands are built-in features of the shell itself, as opposed to a separate program that is executed. Implement the commands listed below. Note that for these you need not fork a new process as they can be handled directly in the parent process. All the commands here are case-sensitive.

exit: Exit the shell program. If the user provided any argument, abort the operation (i.e., command not executed) and display an error message.

pwd: Display the current working directory. Use the getcwd() function. Run man getcwd for more. Again, abort the operation and display an error message if the user provided any argument. cd: Change the current working directory. Use the chdir() function. Pass chdir() the rst argument the user enters (it will accept absolute and relative paths). If the user passed in more than one argument, abort the operation and display an error message. If chdir() returns an error, display an error message.

help: Display help information on internal commands.

If the rst argument is one of our internal commands, print “&lt;argument&gt; is a builtin command” plus a brief description on what the command does. For example, if argument is ‘cd’, the output should be:

If the rst argument is not an internal command, this command prints “&lt;argument&gt; is an external command or application”. For example, if argument is ‘ls’, the output must be:

If there is more than one argument, display an error message

If there is no argument provided, list all the supported internal commands. For each command, include a short summary on what it does.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
// Cleanup any previously exited background child processes // (The zombies)

while (waitpid(-1, NULL, WNOHANG) &gt; 0)

; // do nothing.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>/home/cmpt300$
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
‘cd’ is a builtin command for changing the current working directory.

</div>
</div>
<div class="layoutArea">
<div class="column">
‘ls’ is an external command or application

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Problem 3. History Feature

The next task is to modify your shell to provide a history feature that allows the user access up to the 10 most recently entered commands. Start numbering the user’s commands at 0 and increment for each command entered. These numbers will grow past 9. For example, if the user has entered 35 commands, then the most recent 10 will be numbered 15 through 34.

History Commands: First implement an internal command “history” which displays the 10 most recent commands executed in the shell. If there are not yet 10 commands entered, display all the commands entered so far.

Display the commands in descending order (sorted by its command number).

The output should include both external application commands and internal commands.

Display the command number on the left, and the command (with all its arguments) on the right.

Hint: Print a tab between the two outputs to have them line up easily.

If the command is run in the background using &amp;, it must be added to the history with the &amp;. A sample output of the history command is shown below:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>/home/cmpt300$ history
30      history
29      cd /home/cmpt300
28      cd /proc
</pre>
<pre>27      cat uptime
26      cd /usr
25      ls
24      man pthread_create
23      ls
</pre>
<pre>22      echo "Hello World from my shell!"
21      ls -la
/home/cmpt300$
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Next, implement the ! commands which allows users to run commands directly from the history list:

Command “!n” runs command number n, such as “!22” will re-run the 23rd command entered this session. In the above example, this will re-run the echo command.

If n is not a number, or an invalid value (not one of the previous 10 command numbers) then display an error.

You may treat any command starting with ! as a history command. For example, if the user types “!hi”, just display an error. Note that atoi(“hi”) returns 0, which should not be treated as a valid command.

Command “!!” runs the previous command.

If there is no previous command, display an error message.

When running a command using “!n” or “!!”, display the command from history to the screen so the user can see what command they are actually running.

Neither the “!!” nor the “!n” commands are to be added to the history list themselves, but rather the command being executed from the history must be added. Here is an example.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>/home/cmpt300$ echo test
test
</pre>
</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
<div class="column">
5/8

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
2021/2/2 SFU CMPT 300 – Assignment 1

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Suggestions

Implement history as a global two dimensional array:

Rather than having all your code directly access the history array, write some functions which encapsulate accesses to this array. Suggested functions would include: add command to history, retrieve command (copy into buffer, likely), printing the last 10 commands to the screen.

Signals: Change your shell program to display the help information when the user presses ctrl-c (which is the SIGINT signal). A guide on using signals is available here.

In main(), register a custom signal handler for the SIGINT signal.

Have the signal handler display the help information (same as the help command).

Then re-display the command-prompt before returning.

Note that when another child process is running, ctrl-c will likely cancel/kill that process. Therefore displaying the help information with ctrl-c will only be tested when there are no child processes running.

Suggestions

To implement this, you will also need to change read_command() a little bit.

The signal handler will do nothing but displaying the help information and then display the prompt again. The signal will interrupt the read() system call and discard all data already read for this command.

When read() fails, it returns -1. You can check why read fails: if it returns -1 and the environment variable errno equals EINTR it means that it was interrupted by a signal. If the return value is -1 and errno is any other value, it means read just failed and the program should exit.

</div>
</div>
<div class="layoutArea">
<div class="column">
#define HISTORY_DEPTH 10

char history[HISTORY_DEPTH][COMMAND_LENGTH];

</div>
</div>
<div class="layoutArea">
<div class="column">
To correctly check read()’s return value you can change the code that you now have:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>/home/cmpt300$ !!
echo test
test
/home/cmpt300$ history
15      history
</pre>
<pre>14      echo test
13      echo test
12      ls
11      man pthread_create
10      cd /home/cmpt300
</pre>
9 ls

8 ls -la

7 echo Hello World from my shell! 6 history

/home/cmpt300$

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
<div class="column"></div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
to the following:

Problem 4 (Optional). Better cd Command [15 bonus points]

Note: You must nish Problems 1, 2 and 3 before attempting Problem 4. Submitting Problem 4 alone

without solutions to Problems 1, 2 or 3 will leave you with 0 mark for Problem 4.

Implement the following features that are often supported by the cd command in modern shells (e.g., bash).

Change to the home directory if no argument is provided.

Support ~ for the home folder.

For example, cd ~/cmpt300 should change to the “cmpt300” directory under the current user’s home directory. Issuing cd ~ will switch to the home directory.

Support – for changing back to the previous directory.

For example, suppose that the current working directory is /home and you issued cd / to change to the root directory. Then, cd – will switch back to the /home directory.

Hints: You may nd the getuid and getpwuid functions useful. They allow you to gather useful information about the current user.

3. Notes

You do not need to support either &gt; or | from the terminal. These are features of the normal Linux terminal that we are not implementing. Your code must not have any memory leaks or memory access errors (using Valgrind). Your shell must free all memory before it exits. However, your child processes may exit without freeing all their memory (if exec() fails then the child process will have a copy of all the memory that the parent holds; freeing this memory would be unnecessarily time consuming for the OS). Therefore, you may ignore any Valgrind messages when a child process terminates to the effect of memory being held when program terminated.

4. Resources

Sample code: shell.c, Makele

Guide to Signals

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
if ((length &lt; 0) &amp;&amp; (errno !=EINTR)) { perror(“Unable to read command. Terminating.\n”); exit(-1); /* terminate with error */

}

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
5. Submission

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
if (length &lt; 0) {

perror(“Unable to read command. Terminating.\n”); exit(-1); /* terminate with error */

}

</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
You need to submit a compressed archive named a1.tar.gz to CourSys of your code and a make le (sample code: shell.c, Makele). If you did this assignment in a group, include also a simple readme text le in your package that details each group member’s contributions; each of you should contribute to a reasonable share of the assignment, and every group member will receive the same marks. We will build your code using your make le, and run it using the command: ./shell. You may use more than one .c/.h le in your solution if you like. If so, your Makefile must correctly build your project. Please remember that all submissions will automatically be compared for unexplainable similarities.

Following the steps below to prepare your submission:

Make sure that your les are stored in a directory as called a1

Change to each of your folders and issue the command make clean. This will remove all object les as well as all output and temporary les

Change to your a1 folder:

Then, issue:

which creates a tar ball (i.e., a single le) that contains the contents of the folder. Compress your le using gzip:

Submit via CourSys by the deadline posted there. Grading Policies

Make sure you are familiar with the course policies. Especially, we do not accept late submissions, so please submit on time by the deadline. Your code must compile and run on Linux; you will receive a 0 mark if your code does not compile. Sample solutions will not be provided for assignments. Your code should also not leak any memory; we will check using Valgrind. Any memory leak will lead to 10 marks overall deduction. We will test your code using more complex and hidden test cases, so you are encouraged to vary as many parameters as possible to test your code.

* Created by Mohamed Hefeeda, modied by 436 Brian Fraser, Keval Vora and Tianzheng Wang.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>$ cd ~/cmpt300/a1
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>$ tar cvf a1.tar *
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
$ gzip a1.tar

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://systems.cs.sfu.ca/cmpt300/spring21/assignments/a1/a1.html

</div>
<div class="column">
8/8

</div>
</div>
</div>
</div>
