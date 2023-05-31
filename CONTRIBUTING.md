# Contributing

Contributions are very welcome! In fact, we encourage them. Every little bit helps, and credit will always be given.

The easiest way to contribute is to give this book’s [Github page] a star. You could also tweet about it using the hashtag `#codingforhealthcareprofessionals`. Both of these help others find the book.

Feel free to provide feedback, suggestions, or corrections by raising [issues] on the Github repository for the book. You can also submit [pull requests] with corrections, improvements, or new content.

We ask, however, if you’re thinking of making a contribution, especially of a new page, please open an issue before starting to work on anything. This will give a chance to talk the new content over with the book maintainers.

## Setting Up The Development Environment

This book is created using the excellent open source [Jupyter Book] project.

If you'd like to develop and/or build the Coding for Healthcare Professionals book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the book's source files located in the `coding_for_healthcare_professionals` directory
4. Run `jupyter-book clean coding_for_healthcare_professionals` to remove any existing builds
5. Run `jupyter-book build coding_for_healthcare_professionals`

A fully-rendered HTML version of the book will be built in `coding_for_healthcare_professionals/_build/html/`.

## Submitting Changes

As the `main` is protected, please create a new branch to commit your changes to and then raise a pull request.

## Code of Conduct

Please note that the Coding for Healthcare Professionals book is released with a [Contributor Code of Conduct][code of conduct]. By contributing to this project you agree to abide by its terms.

<!-- Links -->

[github page]: https://github.com/oliverjwroberts/coding_for_healthcare_professionals
[jupyter book]: https://jupyterbook.org/en/stable/intro.html
[issues]: https://github.com/oliverjwroberts/coding_for_healthcare_professionals/issues
[pull requests]: https://github.com/oliverjwroberts/coding_for_healthcare_professionals/pulls

<!-- GitHub Only -->

[code of conduct]: CODE_OF_CONDUCT.md
