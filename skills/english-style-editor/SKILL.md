---
name: english-style-editor
description: >
  Review and edit English text for style, grammar, and clarity using Strunk's
  Elements of Style rules. Use this skill whenever the user asks to check, review,
  edit, proofread, or improve English writing style. Also trigger when the user
  mentions: comma splices, passive voice, wordiness, parallel construction,
  dangling modifiers, misused words, or any request to "tighten up" or "clean up"
  prose. Apply this skill to blog posts, emails, reports, essays, documentation,
  or any English text that should be clear, concise, and correct.
---

# English Style Editor

Review English text against Strunk's *The Elements of Style* — flag violations,
explain the relevant rule, and suggest concrete corrections.

## Review Workflow

1. Read the text the user provides (or the file they point to).
2. Scan for violations across all categories below.
3. Report findings organized by severity:
   - **Errors**: clear rule violations (comma splices, dangling modifiers, incorrect word usage)
   - **Improvements**: places where a principle would strengthen the prose (passive → active, wordy → concise, vague → specific)
   - **Notes**: minor style preferences or judgment calls
4. For each finding, state: the original text (quoted), the rule violated (number and name), why it matters, and a suggested revision.
5. Offer a clean revision of the full text at the end.

**Tone:** Be direct but constructive. Brief, specific, no hedging. Quote the rule, show the fix, move on. If a passage is good, say so and move on.

**Output format:** For short text, give feedback inline. For longer text:

```
## Style Review

### Errors
1. **[Original text]** — Rule 5 (no comma splice): [explanation]. → *[fix]*

### Improvements
1. **[Original text]** — Rule 10 (active voice): [explanation]. → *[fix]*

### Notes
1. **[Original text]** — [observation]

---
## Revised Text
[Full cleaned-up version]
```

---

# PART I: ELEMENTARY RULES OF USAGE (Rules 1–7)

These rules cover punctuation, possessives, and modifier placement. Violations produce objectively incorrect or ambiguous sentences.

## Rule 1: Possessive singular — add 's

Follow this rule regardless of the final consonant: Charles's friend, Burns's poems, the witch's malice.

**Exceptions:** Ancient proper names in -es or -is use "of" form (the heel of Achilles, the laws of Moses, the temple of Isis). The possessive Jesus'. Idiomatic forms: for conscience' sake, for righteousness' sake.

The pronominal possessives hers, its, theirs, yours, oneself have NO apostrophe. Watch for the its/it's error.

## Rule 2: Oxford comma in a series

In a series of three or more terms with a single conjunction, comma after each term except the last: red, white, and blue. He opened the letter, read it, and made a note of its contents.

**Exception:** Business firm names omit the last comma: Brown, Shipley & Co.

## Rule 3: Parenthetic expressions between commas

If an expression interrupts the sentence, it needs commas on BOTH sides. Never one comma without the other.

**Wrong:** Marjorie's husband, Colonel Nelson paid us a visit yesterday,
**Wrong:** My brother you will be pleased to hear, is now in perfect health,

**Always parenthetic:** (1) The year in a date, day of month after day of week. (2) Abbreviations etc. and jr. (3) Non-restrictive relative clauses — clauses that add information but don't identify.

**Restrictive vs. non-restrictive test:** Can you remove the clause and still know what's referred to? Yes → non-restrictive → commas. No → restrictive → no commas.

- Non-restrictive: The audience, which had at first been indifferent, became more interested.
- Restrictive: The candidate who best meets these requirements will obtain the place.

If a parenthetic expression follows a conjunction, put the first comma BEFORE the conjunction: He saw us coming, and unaware that we had learned of his treachery, greeted us with a smile.

## Rule 4: Comma before conjunction in a compound sentence

When two independent clauses are joined by a conjunction (and, but, or, nor, for, as, while), place a comma before the conjunction.

- The early records of the city have disappeared, and the story of its first years can no longer be reconstructed.
- The situation is perilous, but there is still one chance of escape.

**Omit the comma** when the subject is the same and expressed only once, with "and" and a close relationship: He has had several years' experience and is thoroughly competent. But keep the comma with "but": I have heard his arguments, but am still unconvinced.

**Semicolon instead of comma** when the second clause starts with an adverb (accordingly, besides, then, therefore, thus).

**Note on "so":** Colloquial as a connective. Better: omit "so" and begin the first clause with "as" or "since."

## Rule 5: No comma splice

If two grammatically complete clauses lack a conjunction, use a semicolon:

- Stevenson's romances are entertaining; they are full of exciting adventures.
- It is nearly half past five; we cannot reach town before dark.

An adverb between clauses does NOT count as a conjunction — semicolon still required.

**Exceptions:** Very short clauses alike in form (Man proposes, God disposes) and colloquial expressions in dialogue (I hardly knew him, he was so changed).

## Rule 6: Don't break sentences in two

Don't use periods where commas belong — no sentence fragments.

**Wrong:** I met them on a Cunard liner several years ago. Coming home from Liverpool to New York.
**Wrong:** He was an interesting talker. A man who had traveled all over the world.

Replace the period with a comma and lowercase the next word.

**Exception:** An emphatic word or expression may stand alone when emphasis is clearly warranted: Again and again he called out. No reply.

## Rule 7: Dangling modifiers

A participial phrase at the beginning of a sentence MUST refer to the grammatical subject.

**Wrong → Right:**
- On arriving in Chicago, his friends met him at the station. → When he arrived in Chicago, his friends met him at the station.
- A soldier of proved valor, they entrusted him with the defence. → A soldier of proved valor, he was entrusted with the defence.
- Young and inexperienced, the task seemed easy to me. → Young and inexperienced, I thought the task easy.
- Being in a dilapidated condition, I was able to buy the house very cheap. → [Recast entirely.]

Applies equally to participial phrases, prepositional phrases, nouns in apposition, adjectives, and adjective phrases that begin the sentence.

**Test:** Read the opening phrase, look at the subject. Does the phrase describe the subject? If not, rewrite.

---

# PART II: ELEMENTARY PRINCIPLES OF COMPOSITION (Rules 8–14)

These principles govern paragraph and sentence construction. They involve judgment, but the principles are well-established.

## Rule 8: One paragraph, one topic

Each paragraph should treat a single topic. The beginning of each paragraph signals the reader that a new step has been reached.

Single-sentence paragraphs should generally be avoided except for transitional sentences. In dialogue, each speech is its own paragraph.

## Rule 9: Topic sentence first

Begin each paragraph with a topic sentence; end in conformity with the beginning.

Best structure: (a) topic sentence at or near the beginning, (b) succeeding sentences explain/establish/develop the topic, (c) final sentence emphasizes the topic or states an important consequence.

Avoid ending with a digression or unimportant detail.

The topic sentence can be developed by: restating in other forms, defining terms, denying the contrary, giving illustrations, offering proofs, showing implications and consequences.

## Rule 10: Use the active voice

The active voice is usually more direct and vigorous than the passive.

**Passive → Active:**
- My first visit to Boston will always be remembered by me. → I shall always remember my first visit to Boston.
- There were a great number of dead leaves lying on the ground. → Dead leaves covered the ground.
- The sound of a guitar could be heard. → Somewhere in the house a guitar hummed sleepily.
- The reason he left college was that his health became impaired. → Failing health compelled him to leave college.
- It was not long before he was very sorry that he had said what he had. → He soon repented his words.

**Passive patterns to catch:** "A survey was made" → action noun + empty verb. "There is/are..." → recast with concrete subject. Stacked passives: "Gold was not allowed to be exported" → "It was forbidden to export gold."

**When passive IS appropriate:** when the receiver matters more than the doer, when the doer is unknown, or in a paragraph about the thing being acted upon.

## Rule 11: Put statements in positive form

Make definite assertions. Use "not" for denial or antithesis, never for evasion.

- He was not very often on time. → He usually came late.
- not honest → dishonest
- not important → trifling
- did not remember → forgot
- did not pay any attention to → ignored

Antithesis IS strong: Not charity, but simple justice. Other negative words (never, no, none) are usually strong — the weakness is specific to the evasive "not."

## Rule 12: Use definite, specific, concrete language

Prefer the specific to the general, the definite to the vague, the concrete to the abstract.

- A period of unfavorable weather set in. → It rained every day for a week.
- He showed satisfaction as he took possession of his well-earned reward. → He grinned as he pocketed the coin.

Since we think in particulars, a specific term suggests an image immediately, while an abstract word forces the reader to choose from mental stock — wasting effort and dulling the impression.

In narrative: give significant details with definiteness. In exposition: never lose hold of the concrete; give particular instances of general principles.

## Rule 13: Omit needless words

A sentence should contain no unnecessary words, a paragraph no unnecessary sentences — for the same reason that a drawing should have no unnecessary lines and a machine no unnecessary parts. Every word must tell.

**Common violations:**

| Wordy | Concise |
|-------|---------|
| the question as to whether | whether |
| there is no doubt but that | no doubt (doubtless) |
| used for fuel purposes | used for fuel |
| he is a man who | he |
| in a hasty manner | hastily |
| this is a subject which | this subject |
| His story is a strange one. | His story is strange. |

**Eliminate "the fact that":**

| Wordy | Concise |
|-------|---------|
| owing to the fact that | since (because) |
| in spite of the fact that | though (although) |
| call your attention to the fact that | remind you (notify you) |
| the fact that he had not succeeded | his failure |

**"Who is" / "which was" often superfluous:** His brother, who is a member of the same firm → His brother, a member of the same firm.

**Combine step-by-step presentations:** Wordy (51 words) about Macbeth → Concise (26 words): Encouraged by his wife, Macbeth achieved his ambition and realized the prediction of the witches by murdering Duncan and becoming king of Scotland in his place.

## Rule 14: Avoid a succession of loose sentences

Targets loose sentences of two coordinate clauses, the second introduced by and, but, so, who, which, when, where, while. Single loose sentences are fine; a series becomes monotonous. Vary with: simple sentences, semicolon-joined clauses, periodic sentences, three-clause sentences.

## Rule 15: Parallel construction

Expressions of similar content and function should be outwardly similar.

- Formerly, science was taught by the textbook method, while now the laboratory method is employed. → ...by the textbook method; now it is taught by the laboratory method.
- It was both a long ceremony and very tedious. → The ceremony was both long and tedious.
- A time not for words, but action. → A time not for words, but for action.
- Either you must grant his request or incur his ill will. → You must either grant his request or incur his ill will.

Articles and prepositions applying to all members of a series must appear before the first term only or be repeated before each. Correlatives (both...and, not...but, either...or) must be followed by the same grammatical construction.

## Rule 16: Keep related words together

Bring related words together; keep unrelated words apart.

**Subject and verb** should not be separated by a transferable phrase: Wordsworth, in the fifth book of The Excursion, gives... → In the fifth book of The Excursion, Wordsworth gives...

**Relative pronouns** immediately after their antecedent: There was a look in his eye that boded mischief. → In his eye was a look that boded mischief.

**Modifiers** next to the word they modify: All the members were not present. → Not all the members were present. He only found two mistakes. → He found only two mistakes.

## Rule 17: One tense in summaries

In summarizing a drama, use present tense. For poems, stories, novels, prefer present (past acceptable). Don't shift tenses — it suggests uncertainty.

Avoid intercalating "he said," "the speaker added." Indicate once that what follows is summary, then proceed.

## Rule 18: Emphatic words at the end

The strongest position in the sentence is the end.

- Humanity has hardly advanced in fortitude since that time, though it has advanced in many other ways. → Humanity, since that time, has advanced in many other ways, but it has hardly advanced in fortitude.
- This steel is principally used for making razors, because of its hardness. → Because of its hardness, this steel is principally used in making razors.

The other prominent position is the beginning. Any element other than the subject can become emphatic when placed first: Deceit or treachery he could never forgive.

This principle applies equally to words in a sentence, sentences in a paragraph, and paragraphs in a composition.

---

# PART III: WORDS AND EXPRESSIONS COMMONLY MISUSED

When flagging these, suggest the correction AND explain why the original is problematic. The proper course is usually not to patch by swapping words, but to recast the sentence completely.

| Misused | Correct / Better | Note |
|---------|-----------------|------|
| all right (general approval) | detached "Agreed" or "Go ahead" only | Always two words |
| as good or better than | as good as his, or better | Complete the comparison |
| as to whether | whether | "As to" unnecessary |
| but (after doubt/help) | I have no doubt that; could not help seeing that | "But" unnecessary |
| can (for permission) | may | "Can" = ability |
| certainly (intensifier) | omit or strengthen | Mannerism like "very" |
| claim (for declare) | declare, maintain, charge | "Claim" = lay claim to |
| clever (overused) | restrict to ingenuity in small matters | |
| compare to vs. with | TO = resemblances (different orders); WITH = differences (same order) | Life compared to a pilgrimage; Congress compared with Parliament |
| data (singular verb) | data ARE (plural) | Like phenomena, strata |
| dependable | reliable, trustworthy | Needless substitute |
| different than | different from, other than, unlike | "Than" not permissible |
| divided into (for composed of) | composed of (constituent parts) | Plays divided into acts; poems composed of stanzas |
| don't (for doesn't) | doesn't | |
| due to (adverbial) | through, because of, owing to | Correct only as predicate/modifier of noun |
| etc. (after "such as") | omit etc. | Redundant after introductory phrase |
| fact (for judgment) | reserve for verifiable matters | |
| factor (hackneyed) | recast sentence | |
| feature (hackneyed) | recast | Adds nothing |
| fix (in writing) | arrange, prepare, mend | "Fix" in writing = fasten, make firm |
| get (have got for have) | have | Colloquial |
| however (first, meaning nevertheless) | move to second position or later | First = "in whatever way" |
| interesting (preamble) | omit; make content interesting | Don't announce — demonstrate |
| kind of / sort of (for rather) | rather, somewhat | Literal sense only |
| less (for fewer) | fewer (number); less (quantity) | "Fewer men" not "less men" |
| like (before clause) | as | "Like" governs nouns; "as" introduces clauses |
| line, along these lines | recast | Overworked |
| literal/literally (emphasis) | omit | Incorrect intensification |
| lose out | lose | "Out" adds nothing |
| most (for almost) | almost | "Most everybody" → "Almost everybody" |
| one of the most (opening) | avoid as opening | Threadbare |
| participle for gerund | possessive before gerund | "Do you mind my asking" not "me asking" |
| people (for public) | the public (patronage/appreciation) | "The people" = political |
| phase (for aspect) | aspect, point, topic | "Phase" = stage of transition |
| possess (for have) | have, own | |
| respective/respectively | usually omit | |
| shall/will | shall (1st person); will (2nd/3rd) | |
| so (intensifier) | omit or recast | Avoid in writing |
| split infinitive | move adverb | "To inquire diligently" |
| state (for say) | say, remark | "State" = express fully |
| student body | students | |
| system (needless) | recast | "Government by commission" |
| thanking you in advance | "Will you please" or "I shall be obliged" | Sounds dismissive |
| they (singular antecedent) | he or she | After each, everybody, anyone |
| very | use sparingly | Use words strong in themselves |
| viewpoint | point of view | Don't misuse for "view" or "opinion" |
| while (for and/but/although) | and, but, although, or semicolon | Restrict to "during the time that" |
| whom (before "he said") | who (if subject of following verb) | |
| worth while (before noun) | indefensible before a noun | Actions only |
| would (1st person conditional) | should | "I should not have succeeded" |

**Key patterns:** Hackneyed abstractions (factor, feature, character, nature, system, case, line) are usually symptoms of lazy thinking — recast with concrete language rather than swapping words.

---

# PART IV: MATTERS OF FORM AND SPELLING

**Numerals:** Don't spell out dates or serial numbers. Write in figures or Roman notation: August 9, 1918; Rule 3; Chapter XII.

**Parentheses:** Punctuate outside as if the parenthetical were absent. Inside, punctuate as standalone, omitting final stop unless ? or !.

**Quotations:** Formal (documentary) → colon + quotes. Appositive/direct object → comma + quotes. Indirect discourse (introduced by "that") → no quotes. Proverbs, familiar literary phrases, colloquialisms → no quotes needed.

**References:** Abbreviate frequently cited titles. References in parentheses or footnotes, not sentence body. Omit "act," "scene," etc. except when referring by only one.

**Titles:** Italics with capitalized initials. Omit initial A/The when possessive precedes: Dickens's Tale of Two Cities.

**Spelling — doubling rule:** Single consonant (not v) after stressed short vowel doubles before -ed/-ing: planned, letting, beginning. Exception: coming.

**Commonly misspelled:** accidentally, believe, definite, embarrass, existence, fascinate, immediately, mischief, necessary, occurred, parallel, prejudice, privilege, rhythm, sacrilegious, separate, villain.
