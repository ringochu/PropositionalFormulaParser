# PropositionalFormulaParser
PS I just use here to backup my file in any case if it's lost or something.
I took two examples from git on FOL parser.

I don't write fabolous code there's probably places could be improved (eg the propositional formula part in parser)
My general idea is to parse all formula like a binary tree recursively.

1.Check the first and last bracket
2.Locate the binary connective in the middle. Condition is to have one '(' and (.*), which means counts of brackets are one only.
3.parse the formula before the BC and after the BC

f
