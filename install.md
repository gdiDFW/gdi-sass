Before we can compose Sass we need to install it. Sass is built upon [Ruby](http://www.ruby-lang.org/en/).

# 1. Install Ruby
*Mac users, you can skip this step. Ruby comes pre-installed.*

Because Sass is a Ruby gem, the first thing you need to do is install Ruby using [the Windows installer](http://rubyinstaller.org/). Unlike OS X, Ruby is not installed by default on Windows, so Windows users need to install it manually.

When you go through the installation wizard, you’ll come to this options screen:

![](http://mina.is//teaching/gdi/img/sass-step-1.jpg)

From what I can tell, the only option that you need to check on that one is the middle option, which helps your command-line instructions recognize where to find (as it says) “Ruby executables”. Otherwise, you’ll get the error message “ruby is not recognized as an internal or external command” when you try to install Sass in the command prompt (see next step).

# 2. Install Sass
Now that you have Ruby installed, you’ll be able to install Sass. To do this, open the command prompt by doing one of the following:

**On OS X / Linux:**

Go to the Terminal.app and type:
 
	sudo gem install sass

**On Windows:**

- Start–>Run, then type “cmd”; or
- Start–>All Programs–>Accessories, then choose “Command Prompt”

Once the command prompt is open, install Sass by typing the following in the prompt:

	gem install sass

Then hit “enter”, and wait for Sass to be installed. It should look like this when done:

![](http://mina.is//teaching/gdi/img/sass-step-2.jpg)

# 3. Verify

You should now have Sass installed, but it never hurts to double-check. In your terminal application you can type:

	sass -v

It should return ```Sass 3.3.5 (Maptastic Maple)```. Congratulations! You've successfully installed Sass.
