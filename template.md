# Craftseer — Game Template

**user:** What subject shall we explore?

**LLM:** [Subject, or suggestions if the player wants help choosing]

**user:** What aspects of [subject] should the game represent?

**LLM:** [Suggested aspects]

**user:** Select, modify, or define the aspects to use. There is no fixed number.

**LLM:** [Confirmed aspects, expressed as labels or questions]

**user:** Fill each aspect with a single word.

**LLM:** [One-word value for each confirmed aspect, labelled by aspect]

**user:** What relationships should connect these elements? You may propose connections or let the player define them.

**LLM:** [Proposed connections, labelled by source and target, if helpful]

**user:** Confirm or modify the connections, or define your own. There is no fixed number. Give each a single-word relationship.

**LLM:** [Relationships in the form [X] —word→ [Y]]

**user:** Combine the elements and relationships into a statement or structure.

**LLM:** [Composed statement]

**user:** Critique every element and relationship using a single word. Label each relationship as [X] —word→ [Y]. Show each item's original word and its single-word critique, retaining element labels and relationship endpoints.

**LLM:** [Every element's label, original word, and single-word critique; every relationship's endpoints, original word, and single-word critique]

**user:** Reproduce each item's critique and follow it with ⇒. If the critique identifies a weakness, give a single-word replacement after ⇒. Otherwise, write `retain` after ⇒. Preserve the original structure. Use single words for critiques and replacements, and use `retain` only to indicate that the original word stays unchanged.

**LLM:** [Each item's label or relationship endpoints, original word, reproduced critique, and ⇒ followed by a single-word replacement or `retain`]

**user:** Reassemble the improved elements and relationships.

**LLM:** [Revised statement]

**user:** [Further critique, constraint, or iteration request]

**LLM:** [Response that follows the applicable rules and constraints]

*Constraints may be introduced for a particular game. Once established, they must be enforced consistently.*

*Preserve the confirmed elements and connections throughout subsequent steps unless the player changes them.*
