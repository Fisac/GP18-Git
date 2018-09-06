# 02 - Bash

[<img src="https://cloud.githubusercontent.com/assets/499192/19627812/36c6bfc6-9950-11e6-9a73-e58f97ab2aed.gif" alt="It's a Unix system" width="100%">](https://youtu.be/dxIPcbmo1_U)

Today we're going to learn about the [command-line interface](https://en.m.wikipedia.org/wiki/Command-line_interface) and [UNIX](https://en.m.wikipedia.org/wiki/Unix)!

> A [Unix shell](https://en.m.wikipedia.org/wiki/Unix_shell) is a [command-line](https://en.m.wikipedia.org/wiki/Command-line_interface) interpreter or shell that provides a traditional Unix-like command line user interface. Users direct the operation of the computer by entering commands as text for a command line interpreter to execute, or by creating text scripts of one or more such commands.

If you're running Windows, [checkout this article](http://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10).

### Commands

Command | Description
------- | -----------
[`cat`](https://tldr.ostera.io/cat) | Print and concatenate files.
[`cd`](https://tldr.ostera.io/cd) | Change the current working directory.
[`cp`](https://tldr.ostera.io/cp) | Copy files and directories.
[`history`](https://tldr.ostera.io/history) | List the command-line history.
[`ls -la`](https://tldr.ostera.io/ls) | List directory contents.
[`man`](https://tldr.ostera.io/man) | Format and display manual pages.
[`mkdir`](https://tldr.ostera.io/mkdir) | Creates a directory.
[`mv`](https://tldr.ostera.io/mv) | Move or rename files and directories.
[`pwd`](https://tldr.ostera.io/pwd) | Print name of current/working directory.
[`rm -r`](https://tldr.ostera.io/rm) | Remove files or directories.
[`rmdir`](https://tldr.ostera.io/rmdir) | Removes a directory.
[`touch`](https://tldr.ostera.io/touch) | Create files.

### Keyboard Shortcuts

Shortcut | Description
------- | -----------
<kbd>&#8593;</kbd> | Go backwards in history.
<kbd>&#8595;</kbd> | Go forwards in history.
<kbd>ctrl</kbd> + <kbd>a</kbd> | Jump to the beginning of the line.
<kbd>ctrl</kbd> + <kbd>c</kbd> | Kill whatever is running.
<kbd>ctrl</kbd> + <kbd>e</kbd> | Jump to the end of the line.
<kbd>ctrl</kbd> + <kbd>l</kbd> | Clear the current screen.
<kbd>ctrl</kbd> + <kbd>r</kbd> | Search the command history as you type.


## Assignments

1. Open up the command-line and navigate with `cd` to the desktop.

2. Create a new directory on the desktop and name it `bash`.

3. Change the current directory into the newly created `bash` directory.

4. Create a new file within the `bash` directory and name it `index.html`.

5. Create a new directory within the `bash` and name it `shell`.

6. Move the `index.html` file into the `shell` directory.

7. Change the current directory into the `shell` directory and run `pwd` to see the current fullpath.

8. Create a new file within the `shell` directory and name it [`.editorconfig`](http://editorconfig.org).

9. Run the command `ls` with the flags `-la` to view the files in long format and to include [dotfiles](https://askubuntu.com/a/94786) such as the `.editorconfig` file.

10. Now rename the the `.editorconfig` file to [`.gitignore`](https://git-scm.com/docs/gitignore).

11. Now change the current directory up one step `..` into the the `bash` directory.

12. Remove the `shell` directory.

13. Run the `history` command to see what commands you've executed in the past.

## Extra

1. Run the command `man ls` to see what flags you can use with the `ls` command.

2. Make your computer speak out the words [`Hello, I'm Macintosh`](https://youtu.be/8bepzUM1x3w?t=3m).

3. Fetch the history list and remove all items in the list that doesn't include `cd` with [`grep`](https://tldr.ostera.io/grep).

4. Try running this command in your terminal.

    ```sh
    $ telnet towel.blinkenlights.nl
    ```

5. Complete the first three challenges at [Command-line Challenge](https://cmdchallenge.com).

6. Get ready for next week and learn how to use Git on the command-line, with GitHub's interactive course [Try Git](http://try.github.com).

## Resources

- [A command line tutorial](https://www.codecademy.com/learn/learn-the-command-line
) - Codecademy
- [A Guide to Learn Bash](https://github.com/Idnan/bash-guide#readme) - Adnan Ahmed
- [Mastering Bash and Terminal](https://www.blockloop.io/mastering-bash-and-terminal) - Blockloop
- [Online Man Pages](https://tldr.ostera.io/) - tldr
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line#readme) - GitHub
- [Website](https://www.gnu.org/software/bash) - Bash
- [Another installation guide for Windows](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10) - Windows Central
