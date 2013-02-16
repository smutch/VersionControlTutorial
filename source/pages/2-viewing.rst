    commit 98cdaf38c12fccbfe92d4f15dc869afc12792b22
    Author: Simon Mutch <smutch@unimelb.edu.au>
    Date:   Sat Feb 16 15:56:41 2013 +1100
        Delete bibliography.tex.
    commit cc745dbfdf0421c7d84d72c75d3a52c517665fe7
    Author: Simon Mutch <smutch@unimelb.edu.au>
    Date:   Sat Feb 16 15:54:55 2013 +1100
        Add another section, appendix.tex and bibliography.tex.

    commit f615b15149a633c47f690bf891e39cb80029a71b
    Author: Simon Mutch <smutch@unimelb.edu.au>
    Date:   Sat Feb 16 15:51:06 2013 +1100

        Add basic structure of paper.tex
    * 98cdaf3 Delete bibliography.tex. <Simon Mutch>
    * cc745db Add another section, appendix.tex and bibliography.tex. <Simon Mutch>
    * f615b15 Add basic structure of paper.tex <Simon Mutch>
Its useful to be able to have this concise view of the log without having to
type the long command every time.  We can achieve this by adding the command as
an alias.  Try this command::

    % git config --global alias.lg 'log --pretty=format:"%h %s <%an>" --graph'  

Now you can get the concise log view by simply typing::

    % git lg
can get this reference using the ``git lg`` command as outlined above.
    diff --git c/appendix.tex w/appendix.tex
    diff --git c/paper.tex w/paper.tex
    index 3290236..599a0b6 100644
    --- c/paper.tex
    +++ w/paper.tex
    @@ -8,5 +8,8 @@
     \end{document}
    Add a sentence to the section "A New Hope" of ``paper.tex`` but don't
    % git blame paper.tex --date=relative
and you should see a copy of ``paper.tex`` with the reference, author and time