git mv: renaming on case insensitive filesystems
===================

I consider myself a pretty heavy git user but over the years I've never come across the need to rename a file or directory due to a case issue. Today was the day though. OS X is a case insensitive filesystem so it doesn't care if your directory is `./errors` or `./Errors`. However, when you deploy and linux cares about case, you need to rename it to `./Errors`. You can't just rename the directory as git won't see the change. Enter `git mv` to save the day.

`git mv til.txt TIL.txt`

Hat tip to [Stackoverflow](http://stackoverflow.com/a/24979063/267173) per usual.
