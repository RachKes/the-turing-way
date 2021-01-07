(rr-ci)=
# Continuous integration

| Prerequisite | Importance | Notes |
| -------------|------------|-------|
| [Experience with the command line](https://programminghistorian.org/en/lessons/intro-to-bash) | Necessary | Continuous integration will follow command line instructions
| [Version control](./version-control) | Necessary | Continuous integration runs every time a new _commit_ is made to your project |
| [Reproducible computational environments](./reproducible-environments) | Necessary | Continuous integration runs your tests on a separate computer (usually in the cloud) so you need to set it up in the same way. |
| [Testing](./testing) | Very helpful | Continuous integration _tests_ if anything important has changed when you make a change in your project |

## Summary

Continuous integration (CI) is the practice of integrating changes to a project made by individuals into a main, shared version frequently (usually multiple times per day). CI software is also typically used to identify any conflicts and bugs that are introduced by changes, so they are found and fixed early, minimising the effort required to do so. Running tests regularly also saves humans from needing to do it manually. By making users aware of bugs as early as possible researchers (if the project is a research project) do not waste a lot of time doing work that may need to be thrown away, which may be the case if tests are run infrequently and results are produced using faulty code.

## How this will help you/ why this is useful

CI has a number of key benefits:

- Helps bugs to be found early, minimising their damage and making them easier to fix
- Keeps project contributors up to date with each other's work so they can benefit from it as soon as possible
- Encourages users to write tests
- Automates running of tests
- Ensures tests are run frequently