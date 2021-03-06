# How to contribute

Contribution is restricted to INSA 3BIM 2019-2020 winter semester students

## Submitting changes

Please send a [GitHub Pull Request to INSA3BIMCovid19](https://github.com/samubernard/INSA3BIMCovid19/pull/new/master) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

Multiple-author commits are possible by adding two empty lines ('>') and typing 'Co-authored-by: name <name@example.com>' for each co-author

    $ git commit -m "Refactor usability tests.
    >
    >
    Co-authored-by: name <name@example.com>
    Co-authored-by: another-name <another-name@example.com>"

## Coding conventions

Start reading our code and you'll get the hang of it. We optimize for readability:

  * We indent using four spaces (Matlab standard)
  * We always put spaces after list items and function parameters (`[1, 2, 3]`, not `[1,2,3]`), around operators (`x = 1`, not `x=1`), and around hash arrows.
  * This is open source software. Consider the people who will read your code, and make it look nice for them. It's sort of like driving a car: Perhaps you love doing donuts when you're alone, but with passengers the goal is to make the ride as smooth as possible.

Thanks,
Samuel
