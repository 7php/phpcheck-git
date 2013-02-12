===============
GIT - PHP check
===============

:Author: Remigijus Jarmalavicius <remigijus(a)jarmalavicius.lt>
:Thanks to: Vytautas Povilaitis <php-checker(a)vytux.lt>
:Thanks to: hkdobrev (https://github.com/hkdobrev)

About
-----
GIT hook for PHP parse errors checking before commit.

If you looking same thing for Mercurial DCVS, check this out:

    http://www.bitbucket.org/vytux/mercurial-plugin-4-syntax-checking

How to install
--------------
To install hook, copy pre-commit file to your project .git/hooks/pre-commit:

    $ cp pre-commit .git/hooks/pre-commit;
    $ chmod +x .git/hooks/pre-commit;

Now, when you will make some modifications for code and will try to commit, GIT
will stop you and tells where problem exist.

Bugs
----
If you have found any bugs, please track them here:

    https://github.com/ReekenX/git-php-syntax-checker/issues

Thanks for all peoples who made this tool better.
