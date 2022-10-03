# Class 2 Reading Notes - *The Coder's Computer*

*Please refer to the [Mac Terminal Command Cheat Sheet](https://www.makeuseof.com/tag/mac-terminal-commands-cheat-sheet/) as a reference when navigating the terminal.*

## Choosing A Text Editor

A *text editor* is software that allows you to write and manage text which is primarily used for building websites or applications. There are a myriad of options to choose from similar to how when choosing to buy a computer there are are seemingly endless options to sift through before landing on a decision. 

### **What Features are Important in a Text Editor?**

 1. *Code Completion*
    - Feature in some text editors which displays possible suggestions once you begin typing. This *is similar to how your phone will display word suggestions when typing out a text message. Code completion will also finish closing tags/brackets/quotation marks for a user which is easily forgotten when writing code. VS Code, the text editor, being used in this class is especially helpful because it has Emmet built in which is a plug-in that allows you to type in shorthand and click on possible options which reveal long sections of intended code.

2. *Syntax Highlighting*
    - Highlighting is essential for developers who may be staring at a computer for long stretches. This feature changes the color of text. This allows for you to differentiate bewteen different sections of text and identify errors more easily.

3. *Variety of Color Themes*
    - *Color themes* are similarly important so that text is easier to read and pouring over dense code is less tedious. Web/software developers frequently use dark backgrounds and brightly colored text. It's almost like a scene from ***The Matrix***. ![Coding picture](https://images.pexels.com/photos/546819/pexels-photo-546819.jpeg?auto=compress&cs=tinysrgb&w=800)

4. *Option to Choose from Extensions When Needed*
    - Adding extensions to a text editor allows for further customization. Some features that can be added include spell checkers, history logs which track changes, bookmarking within code, debugging, and more.

### Software that already comes with a Computer

All computers have basic built-in text editors. Mac computers use "Text Edit", Windows computers use "Notpad", and Linux computers have different text editors depending on which distrubtion you get. The above text editors will be missing many features that make coding more efficient such as syntax highlighting, code completion, etc.

### Third-Party Options

#### NotePad++

- Cost: Free!
- Computer: Windows ONLY
- Features: syntax highlighting, code completion, word completion, function completion, zoom in/out, and a searchable wiki page. 

#### BB Edit

- Cost: 30-day free trial & then $49.99 for a full license
- Computer: Mac ONLY
- Features: code completion, live previews, syntax highlighting, and more.

#### Visual Studio Code (VSCode)

- Cost: Free!
- Computer: Windows, Mac, and Linux
- Features: Emmet shorthand for HTML & CSS, syntax highlighting, themes, extensions, and code completion.

#### Atom

- Cost: Free!
- Computer: Windows, Mac, and Linux
- Features: syntax highlighting, themes, extensions, and more.

#### Brackets

- Cost: Free!
- Computer: Windows, Mac, and Linux
- Features: Only supports HTML, CSS, and JavaScript.

#### Sublime Text

- Cost: Free or $70 for full license
- Computer: Windows, Mac, and Linux
- Features: syntax highlighting, code completion, themes, and extensions.

### The Difference Between Text Editors and IDEs

An IDE or Integrated Development Environemnt) is a combination of software which serves as a text editor, file manager, compiler, and debugger all in one. This concept is similar to Gmail or Microsoft Outlook which act as an email server, calendar, task manager, and more.

## The Command Line or Terminal

### What is a command line or terminal?

A **command line** or **terminal** is an interface which can control your computer using text commands or codes.

### Opening a Terminal

This action varies based on your computer system so lets run through some options.

- Mac: navigate to **Applications --> Utilities** then click on **Terminal**. Another option is to click `command + space` on your keyboard (this opens the Spotlight Search option on a Mac) then type **Terminal** into the search bar.
- Linux: navigate to **Applications --> System** or **Applications --> Utilitites** to find the **Terminal**

### The Shell, Bash

A terminal has a *shell* which is a part of the OS (operating system) which defines how a terminal looks and behaves after running an entered command by a user. There are multiple types of *shells* available however the most common one is ***bash*** (Bourne again shell).

## Basic Navigation

For helpful terminal commands refer to the *cheat sheet* at the top of this note.

### Paths

A file or directory on a terminal is also a *path*. A path is way to get to or access a particular file/folder/directory in your system. There are two (2) types of paths: **absolute** and **relative** paths.

A file system is a hiararchical structure similar to a tree's root system or a genealogical family tree. The top of the system is known as the **root directoy** which is marked by a forward slash (/). Under this root directory or subdirectories which can continue to branch off.

- **Absolute Paths**: specifiy a file/directory in relation to the root dircotry
- **Relative Paths**: specifiy a file/diretory in relation to where the user is currently located in a system.