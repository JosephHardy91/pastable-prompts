
Read the current document before writing anything, and copy removed lines exactly from it. If it's a file, give line numbers from before any edit.

Write each item in this format, in the agreed order:

### N. <the edit, as an action> (<where>)

**Why:** <one short paragraph>

```diff
  <unchanged line, kept only to show where the edit goes>
- <removed line>
+ <added line>
```

<a sentence or two after the diff, only when needed>

Format details:
- The heading names the edit, not the problem: "Remove the old argument from X", not "X is redundant". <where> names the section of every place the item touches, with line numbers if the document is a file.
- The Why paragraph covers what is wrong now, what goes wrong because of it for the person reading the document, what evidence shows it (a specific case, or say there is none), and why this edit is the right size.
- The diff shows only what changes, never a whole section. Use "..." for the untouched rest of a line. If an item touches several places, put a label line before each place inside the block: `  <where>, after "<sentence>":`.
- The sentences after the diff are for: an optional extra edit, with its own small diff; which item makes an edit that two items share; or a further edit you considered and decided against, with the reason.
- An item that needs no edit gets only its heading and its Why, which names the items that cover it.
- At most one line before the first item. No closing summary. If you noticed something outside the agreed items, list it briefly at the end.

The edits:
- Make the smallest edit that fixes the item. Don't rewrite the text around it or fold in other fixes.
- Before adding text, check that the document doesn't already say it. If it does, drop the edit and say where it's already said.
- Use the document's own terms, names, reference style and tense, and one name for one thing.
- State each rule in one place. If an edit moves a rule, remove it from the old place in the same item.
- An addition takes on the scope of the passage it lands in. If it should apply more widely than that passage, give it its own paragraph and say what it applies to.
- Each addition must make sense where it sits: nothing that refers to text further down, and nothing that leans on another section to carry its meaning.
- Don't add text that rules out a misreading nobody has made.
- Check every fact an addition states (a path, a line number, a quote, a figure) against its source.

The Why:
- Plain words, one idea per sentence, no chains of comma clauses.
- Every "it", "this" and "they" points at one thing. When in doubt, repeat the noun.
- Say what goes wrong, not a label for it: what the reader will do, not "unclear" or "redundant".
- Give an example as an example, not as the only case.
- Don't restate the diff in prose.
