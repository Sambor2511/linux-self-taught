# linux-self-taught

Resource: https://linuxjourney.com/lesson/linux-history

In 1969, Ken Thompson and Dennis Ritchie of Bell Laboratories developed the UNIX operating system. It was later rewritten in C to make it more portable and eventually became a widely used operating system.

A decade or so later, Richard Stallman started working on the GNU (GNU is Not UNIX) project, the GNU kernel called Hurd, which unfortunately never came to completion. The GNU General Public License (GPL), a free software license, was also created as a result of this.

The kernel is the most important piece in the operating system. It allows the hardware to talk to the software. Kernel controls pretty much everything that happens on your system.

Then in 1991, a young fellow named Linus Torvalds started developing what we now know today as the Linux kernel.

### Linux Distribution

WSL

A Linux system is divided into three main parts:

Hardware - This includes all the hardware that your system runs on as well as memory, CPU, disks, etc.
Linux Kernel - As we discussed above, the kernel is the core of the operating system. It manages the hardware and tells it how to interact with the system.
User Space - This is where users like yourself will be directly interacting with the system.

The shell is basically a program that takes your commands from the keyboard and sends them to the operating system to perform. If you’ve ever used a GUI, you’ve probably seen programs such as “Terminal” or “Console” these are just programs that launch a shell for you. Throughout this entire course we will be learning about the wonders of the shell.

Some cmd: ( -a : all, -l : detailed information ) ( can also combine -a and -l to make -al or -la )

pwd : print working directory

cd : change directory

ls : list directory

touch <> : make new file

file <> : show description of the file

cat <> : display file content

less <> : view file content with more tool.

  q - Used to quit out of less and go back to your shell.
  
  Page up, Page down, Up and Down - Navigate using the arrow keys and page keys.
  
  g - Moves to beginning of the text file.
  
  G - Moves to the end of the text file.
  
  /search - You can search for specific text inside the text document. Prefacing the words you want to search with /
  
  h - If you need a little help about how to use less while you’re in less, use help.
  
clear : clear the shell

cp <> <> : copy

mv <> <> : move

mkdir <> : make new directory

rm <> : remove ( have -f, -i, -r)

  rmdir <> : for removing directory
  
find <> <> <> : find file

help <> : print out some guide

man <> : manual guide

whatis <> : short description of the command

alias <> : map some word to a command

exit, logout : exit the shell
