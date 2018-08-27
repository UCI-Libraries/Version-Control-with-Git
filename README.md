# Version Control with Git

UCI Libraries

Wednesday November 14, 2018

1:00 - 5:00 PM

Instructor(s): Danielle Kane, Mitchell Brown

<b><a href="https://www.eventbrite.com/e/version-control-with-git-tickets-49566916983">REGISTER HERE</a></b>

**Please note that this workshop is being held over 2 days! By registering for the workshop you are registering for both days.**

**General Information:** Version control is the lab notebook of the digital world: it’s what professionals use to keep track of what they’ve done and to collaborate with other people. Every large software development project relies on it, and most programmers use it for their small jobs as well. And it isn’t just for software: books, papers, small data sets, and anything that changes over time or needs to be shared can and should be stored in a version control system.

**Who:** The course is aimed at graduate students and other researchers, including undergrads, faculty, staff and community members. <b>You don't need to have any previous knowledge of the tools that will be presented at the workshop.</b> 

**Where:** Langson Library Rm 570. Get directions with <a href="https://www.openstreetmap.org/#map=17/33.64745/-117.83871">OpenStreetMap</a> or <a href="https://goo.gl/maps/528F8BGTYvJ2">Google Maps</a>.

**When:** November 14, 2018 <a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=MWRzMnFiMms3NnB1ZnFzNXFmcW5idDIxOWUga2FuZWRAdWNpLmVkdQ&amp;tmsrc=kaned%40uci.edu"><img border="0" src="https://www.google.com/calendar/images/ext/gc_button1_en.gif"></a>Add to your Google Calendar</a>.

**Requirements:** Participants must bring a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed below). 

**Accessibility:** We are committed to making this workshop accessible to everybody. The workshop organisers have checked that:

    The room is wheelchair / scooter accessible.
    Accessible restrooms are available.

Materials will be provided at the workshop and large-print handouts are available if needed by notifying the organizer in advance. If I can help making learning easier for you (e.g. sign-language interpreters, lactation facilities) please get in touch (using contact details below) and we will attempt to provide them.

**Contact:** Please email Danielle Kane at kaned@uci.edu for more information.

**Syllabus:**

1. Automated Version Control
2. Setting Up Git
3. Creating a Repository
4. Tracking Changes
5. Exploring History
6. Ignoring Things 
7. Remotes in GitHub
8. Collaborating 
9. Conflicts

**Setup**

You will need access to the software described below. In addition, you will need an up-to-date web browser.

In this lesson we use Git from the Unix Shell.  Some previous experience with the shell is expected, but isn't mandatory.

**The Bash Shell**

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.

    <a href=" https://gitforwindows.org/">Download the Git for Windows installer</a>.
    Run the installer and follow the steps bellow:
        Click on "Next".
        Click on "Next".
        Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
        Click on "Next".
        Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
        Keep "Use Windows' default console window" selected and click on "Next".
        Click on "Install".
        Click on "Finish".
    If your "HOME" environment variable is not set (or you don't know what this is):
        Open command prompt (Open Start Menu then type cmd and press [Enter])
        Type the following line into the command prompt window exactly as shown:

        setx HOME "%USERPROFILE%"
        Press [Enter], you should see SUCCESS: Specified value was saved.
        Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program. 

Mac OS X: The default shell in all versions of Mac OS X is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities). See the Git installation video tutorial for an example on how to open the Terminal. You may want to keep Terminal in your dock for this workshop. 

Linux: The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything. 

<b>Git</b>

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. You will need a supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

You will need an account at github.com for parts of the Git lesson. Basic GitHub accounts are free. We encourage you to create a GitHub account if you don't have one already. Please consider what personal information you'd like to reveal. For example, you may want to review these instructions for keeping your email address private provided at GitHub.

Windows: Git should be installed on your computer as part of your Bash install (described above).

macOS: For OS X 10.9 and higher, install Git for Mac by downloading and running the most recent "mavericks" installer from this list. After installing Git, there will not be anything in your /Applications folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available here.

Linux: If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run sudo apt-get install git and for Fedora run sudo dnf install git.

<b>Text Editor</b>

When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like automatic color-coding of key words. The default text editor on macOS and Linux is usually set to Vim, which is not famous for being intuitive. if you accidentally find yourself stuck in it, try typing the escape key, followed by :q! (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell.

Windows:  nano is a basic editor and the default that instructors use in the workshop. To install it, download the Software Carpentry Windows installer and double click on the file to run it. This installer requires an active internet connection. Other editors that you can use are Notepad++ or Sublime Text. Be aware that you must add its installation directory to your system path. 

macOS: nano is a basic editor and the default that instructors use in the workshop. See the Git installation video tutorial for an example on how to open nano. It should be pre-installed. Other editors that you can use are Text Wrangler or Sublime Text.

Linux: nano is a basic editor and the default that instructors use in the workshop. It should be pre-installed. Other editors that you can use are Gedit, Kate or Sublime Text.
