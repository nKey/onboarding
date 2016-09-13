*Git commit messages*

_*Format:*_

```
Capitalized short summary [50 chars max]
[blank line]
Detailed explanation, punctuated. [wrap text at 72 chars]

Multiple lines are ok, as are blank lines.
Jira issue reference (url or just issue code).
[blank line]

```


_*Style:*_

- Capitalize text
- Write your commit message in the imperative: "Fix bug" and not "Fixed bug" or "Fixes bug."
- Summary does not use line end punctuation (remember, it is a title, not a phrase)


_*Example:*_

```
User model perform email regex and fix crash

Also did some work on the thing at the code, caused by the edit at
line 22. Will try to keep code style this way from now on.

PS: Remember to clean up the cat litterbox before compilation.

Closes jira/PROJECT-117.


```


_*References:*_

http://chris.beams.io/posts/git-commit

http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
