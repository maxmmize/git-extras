git-graft(1) -- Merge commits together
======================================

## SYNOPSIS

`git-graft` &lt;src-branch&gt; [&lt;dest-branch&gt;]

## DESCRIPTION

  Merge commits from &lt;src-branch&gt; into &lt;dest-branch&gt; which defaults to &lt;master&gt;.

## OPTIONS

  &lt;src-branch&gt;

  &lt;dest-branch&gt;

## EXAMPLES

    $ git graft new_feature dev
    $ git graft new_feature

## AUTHOR

Written by Kenneth Reitz &lt;<me@kennethreitz.com>&gt;

## REPORTING BUGS

&lt;<http://github.com/visionmedia/git-extras/issues>&gt;

## SEE ALSO

&lt;<http://github.com/visionmedia/git-extras>&gt;
