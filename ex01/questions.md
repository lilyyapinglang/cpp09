1. what is an ``inverted Polish mathematical expression`?

An inverted Polish mathematical expression (commonly known as Reverse Polish Notation (RPN) or postfix notation) is a method of writing math formulas where every operator comes after its operands rather than between them
• Infix Notation (Standard): 3 + 4 (operator is in between numbers)
• Prefix / Polish Notation: + 3 4 (operator is before numbers)
• Reverse Polish / Postfix Notation: 3 4 + (operator is after numbers)


2. how does it work ?

How It Works (Examples)

• Simple Addition:
	• Infix: 3 + 4
	• RPN: 3 4 +
• With Multiple Operations:
	• Infix: (3 + 5) * (7 - 2)
	• RPN: 3 5 + 7 2 - *
• Order of Operations:
	• Infix: 3 - 4 * 5
	• RPN: 3 4 5 * -

3. Why introducing this kind of expression ? 

Main Benefits

• No Parentheses Needed: Brackets and precedence rules (like PEMDAS/BODMAS) are completely unnecessary because the order of evaluation is strictly defined by the sequence.
• Stack-Based Evaluation: Computers and RPN calculators (such as historic Hewlett-Packard models) read the expression from left to right, pushing numbers onto a "stack" and popping them off whenever an operator is reached