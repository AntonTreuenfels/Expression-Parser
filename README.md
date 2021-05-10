# Expression-Parser

A step-by-step approach to parsing expressions from infix to postfix (Reverse Polish)

This series presents a parser of the kinds of expressions commonly found in computer languages, along with an accompanying evaluator of any successfully parsed expressions. The presentation is in a step by step fashion, starting with a parser which does nothing but echo its input and culminating in one that can handle the ternary conditional operator with both string and numeric operands.

This is largely a practical demonstration. There is almost no discussion of theory regarding grammars, Backus Naur Form (BNF), LL(n) versus LR(n) parsers, abstract syntax trees, top-down versus bottom-up parsing, and so on. Instead the emphasis is on making the parser do something, then making it do a little more, and so on, until eventually it meets the goals established for it.

What discussion there is focuses mainly on what the current step is supposed to accomplish, what problems are faced, what alternatives might be used to solve them, and why a particular solution was selected. The goal of any particular step is dictated mainly by what I found interesting or wanted to learn more about. The resulting sequence is leisurely and discursive. I will not argue that any of this results in the best possible parser. What is presented here is merely one approach to solving the general problem.

The language used is Python 3.0. The content is provided in Jupyter notebooks, one for each step. There are also pass and fail tests for steps which introduce new capabilities.
