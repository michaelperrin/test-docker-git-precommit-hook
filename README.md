# Test

Enable Git pre-commit hook:

    rm -R .git/hooks
    ln -s ../bin/git/hooks .git/hooks

How to test:

* Edit README.md file
* `git add README.md`
* `git commit -m "Test"`
