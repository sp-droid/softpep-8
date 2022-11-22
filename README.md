# SoftPEP-8
The SoftPEP-8 full guide can be found in this main/softpep-8.md

This is a public revision on the almost universally adopted Python Enhancement Proposal - 8, also known as Python's Style Guide. Changes can be accepted by anyone if justified and discussed.

# Motives
Coding conventions are essential to make our projects easy to read, interpret and edit. They also serve as templates that companies employ to force some degree of consistency on their employees with the aim of increasing productivity. But sometimes they can become too rigid for the times we live in, and this is exactly the point. 

It is even stated in PEP-8 that actions against their guidelines that at the same time improve code readability SHOULD be considered aswell. Sadly, in many instances, the rules are enforced without taking this flexibility into account, leading to sub-optimal situations. Quote:

> "However, know when to be inconsistent – sometimes style guide recommendations just aren’t applicable. When in doubt, use your best judgment. Look at other examples and decide what looks best. And don’t hesitate to ask!
>
> In particular: do not break backwards compatibility just to comply with this PEP!
>
> Some other good reasons to ignore a particular guideline:
>
> - **When applying the guideline would make the code less readable, even for someone who is used to reading code that follows this PEP.**
> - To be consistent with surrounding code that also breaks it (maybe for historic reasons) – although this is also an opportunity to clean up someone else’s mess (in true XP style).
> - Because the code in question predates the introduction of the guideline and there is no other reason to be modifying that code.
> - When the code needs to remain compatible with older versions of Python that don’t support the feature recommended by the style guide."

**TL;DR: The aim of this style guide is to add exceptions to the rules, so we may code in a more flexible environment but at the same time knowing exactly what to do, removing the vague notion (that helps nobody) of**:
> "When applying the guideline would make the code less readable, even for someone who is used to reading code that follows this PEP."

# Summary of changes to PEP-8
- The entire guide is now a bit more straight to the point
- Added examples to parts that did not have them
### Code lay-out
- Promoted tabs instead of discouraging them
- Allowed argument "self" in first line allowed in hanging indentation
- Not allowed multiple type-hinted arguments per line in hanging/vertical indentation
- Allowed if one-liners
- Not allowed if multilines without an extra level of indentation, to be consistent with functions
- Encouraged multiline calls and definitions with an extra level of indentation, for the same reason
