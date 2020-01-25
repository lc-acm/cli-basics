## Chapter 3: CLI Editors

When editing software, you won't always have access to an IDE or even a graphical user interface (GUI). Becoming proficient in a CLI text editor will be of great benefit to you in your academic and professional career.

The biggest challenge that comes with using a CLI text editor is that you can't typically use the mouse. All text navigation and manipulation must be done with the keyboard.

The text editors below each have their own approach to editing text on the command line. It's up to you to pick one a that suites you best.

### Emacs
Emacs is the preferred text editor of Professor Jeff Ely. It is widely available on Linux and Unix systems and has support for a GUI on top of the CLI.

Emacs can be used intuitively so long as you have access to a GUI. However the real power of Emacs is in it's keyboard commands and extensibility with Lisp.

Here are some basic commands in Emacs:

 - To save the file, hold `CTRL` and type `x` then `s`
 - To quit emacs hold `CTRL` and type `x` then `c`
 - To move the cursor backwards, forwards, up or down, hold `CTRL` and type `b`, `f`, `p` or `n` respectitvely.

To understand Emac's potential, you'll need to learn more of the basics. Here are some resources to get started with Emacs:
 
 - Open emacs and select the `Emacs Tutorial` link to follow the offical Emacs tutorial.
 - [A Guided Tour of Emacs](https://www.gnu.org/software/emacs/tour/) 

### Vim

Vim is the preferred text editor of Professor Michael Harmon (to the dismay of Professor Ely). If you are working on a Linux or Unix system, it is almost guaranteed that the Vim or it's precursor, Vi, is already installed.

Vim is the default text editor for [Git](https://git-scm.com/), so you may be one of the unlucky few that gets "stuck" in Vim while trying to write your first commit message. As you try to type out your message, you'll find that the keyboard does not behave the way you expect. You then scratch your head trying to figure out how to close Vim. How useless!

To use Vim, you must understand that it is *modal*. There are three principal modes that change how the keyboard behaves.

1. **Normal** mode is for navigating and executing commands. For example you can move the cursor left, down, up and right with `h`,`j`, `k` and `l` respectively. You can always get back to normal mode by pressing the `esc` key.

2. **Insert** mode lets you type with keyboard as you'd expect. To go from normal mode to insert mode, press `i`.
 
3. **Visual** mode is for selecting and modifying blocks of text. Enter visual mode by typing `v`.

But why do we need anything more than an "insert" mode? One of Vim's great insights is that you spend a minority of your time writing out new text, and a majority of you time navigating and modifying existing text.
 
To give you a taste of Vim's modal approach, here's what you need to do to edit and save a Git commit message once Vim is open:

1. Vim starts you in normal mode so type `i` to enter insert mode.
2. Type out your commit message.
4. Hit `esc` to enter normal mode.
5. Type out `:w` and press `enter` to save or "write" the file.
6. Type out `:q` and press `enter` to quit vim.

And voila! To understand Vim's potential you'll need to learn more of the basics. Here are some resources to get started with Vim:

 - Run `vimtutor` to follow the offical Vim tutorial
 - [OpenVim Interactive Tutorial](https://www.openvim.com/tutorial.html)
 
### Nano
Nano is easy to use and widely available on Linux systems but not as powerful as Emacs or Vim. If you need a straight forward CLI text editor, Nano is what you are looking for.

Nano conveniently lists some basic commands at the bottom of the window. It's not ideal for heavy software development, but it can help you edit a file in a pinch on the command line.

Resources to get started:
 
 - Open Nano and hold `CTRL` with `G` to open the `Get Help` page.






