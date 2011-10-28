# DESCRIPTION

**focus** is a little bash script aimed to take notes of things you want to stay focused on.

# USAGE

Stay focused on what really matters with **focus on**:

    >> focus on Learn git
    >> focus on LU method

which gives:

     1  [29/10/11] Learn git
     2  [29/10/11] LU Method

You can add tags with **@tag**:

    >> focus on Electromagnetism courses MIT @physics
    >> focus on RK4 @math


and then filter them with **focus on @tag**:

    >> focus on @physics

which gives:

     3  [29/10/11] Electromagnetism courses MIT @physics

Once you're done just **focus off** and specifies the number of the task:

    >> focus off 1

    Finished: 1 [29/10/11] Learn git


# INSTALL

Copy the script into a directory present in your PATH environment variable. Make it executable if necessary.

# CONFIGURATION

Specify the path to the file where your notes will be stored in focus:

        FILE=path/to/my/focus/file
