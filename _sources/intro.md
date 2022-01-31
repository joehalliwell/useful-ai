# Overview

This is an opinionated guide to building Artificial Intelligence (AI) systems
that do useful work in the world.

```{note}
For brevity, we'll use "AI" to refer to our subject matter, but as will become
abundantly clear, this guide concerns systems that have a large Machine
Learning (ML) component.
```

## Who is this for?

You hopefully.

The guide is written from the perspective of an AI practitioner, but it's intended
to be useful for anyone interested in building or helping to build AI
systems that do useful work. Including:

- Business sponsors
- Subject matter experts (SME)
- Product designers
- Software engineers

## The Real AI Fallacy

By definition, building AI systems is tricky. We resort to AI when we don't
understand a problem well enough to write a regular program to solve it.

Indeed when we do figure out how to solve such a problem, the solution is often
discounted as no longer being
["Real AI"](https://en.wikipedia.org/wiki/AI_effect):

```{epigraph}
Every time we figure out a piece of it, it stops being magical; we say, "Oh,
that's just a computation."

-- Rodney Brooks
```

This flawed concept of "Real AI" is at the root of many obstacles to building
useful AI systems. It:

- Misleads stakeholders and sets AI projects up for failure -- sometimes in
  spite of their success! These issues around expectation management are
  discussed in {doc}`people`.
- Focusses attention on how AI systems differ from regular software, frequently
  at the expense of the commonalities. Some of the consequences of this are
  discussed in {doc}`engineering`.
- Finally, and perhaps most perniciously of all, it can confuse practitioners
  themselves. This results in irrational behaviour, resentment, tension, and
  failure. Some strategies and tactics for combatting this are discussed in
  {doc}`research`.

## Credits

This project is created using the excellent open source
[Jupyter Book project](https://jupyterbook.org/) and the
[executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).

## Further reading

- [The Turing Way](https://the-turing-way.netlify.app/welcome.html)
