# Stochastic Methods — Exercises and Solutions

By **Pietro Forni and Riccardo Visconti**, based on *Introduction to Probability Models* by **Sheldon M. Ross**. These are unofficial study notes containing **306 exercises**, with independently written solutions to prepare for the Stochastic Methods exam at USI.

## Study purpose

These notes are intended solely as study material for learning, practice, and revision alongside the textbook. They are independently prepared, unofficial student notes; no endorsement by the textbook author, publisher, or university is claimed.

## Read

- [Exercises only](exercises.pdf)
- [Exercises and solutions](exercises-and-solutions.pdf)

The exercise numbers restart within each topic. Use the topic title and exercise number when reporting a correction.

## Edit and compile

The project has one LaTeX entry point, `main.tex`, and a `chapters/` folder. All shared formatting and the title page are in `main.tex`.

Upload `main.tex` and `chapters/` to Overleaf, or compile locally with a LaTeX installation:

```sh
latexmk -pdf main.tex
```

Near the top of `main.tex`, use `\toggletrue{showsolutions}` for exercises and solutions, or `\togglefalse{showsolutions}` for exercises only. Compile after changing this setting and save the resulting PDF under the corresponding name above. The supplied source defaults to showing solutions.

## About the exercises

The collection has received a first mathematical review. Some statements have been adapted or supplied with explicit assumptions so that they are self-contained. Markov Chains 9 specifies a two-ball replacement urn; Markov Chains 53 specifies a three-level annual insurance premium model. These are chosen models for these notes, not claims about the exact contents of a particular textbook edition. Other formerly implicit models and definitions are now stated in the exercises themselves.

Corrections are welcome: identify the topic and exercise number and explain the proposed change.

## License

The authors' original solutions and LaTeX material are licensed under the [MIT License](LICENSE). Attribution to Ross's textbook is retained; this license does not grant rights to third-party textbook material.

The MIT license and textbook attribution do not establish permission to republish the book’s exercise statements. The collection’s educational purpose alone does not establish public-distribution rights.
