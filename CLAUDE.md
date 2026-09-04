# Clarity Clicks

Local SEO and AI visibility for service businesses in Greater Johannesburg. The repo holds the
marketing site (`index.html`) and the sales playbook (`docs/SALES-PLAYBOOK.md`).

## Writing rule: always run the humanizer pass

Every piece of prose written for this repo goes through the `/humanizer` skill before it is
saved. Invoke the skill, apply it, then write the file. This is not optional and does not need
to be asked for each time.

Applies to the sales playbook, pitch and outreach copy, site copy, README and docs prose, commit
message bodies, and pull request descriptions. Does not apply to code, config, data, or link
targets.

The patterns that keep showing up in this repo, so check these first:

- No em dashes or en dashes. Use a comma, colon, period, or parentheses. Write ranges as "65 to
  80 words", not "65 to 80" with a dash.
- No bullet lists where every item starts with a bold label and a colon. Write prose, or write
  full sentences in a plain list.
- No "not X, but Y" or "it isn't X, it's Y" constructions.
- No announcing a point before making it. Drop "here's the thing", "let's look at", "concretely",
  "take this seriously".
- No rows of dramatic one-line fragments. One short sentence for emphasis is fine.
- No figurative sayings standing in for a plain claim, such as "X is the language of Y".
- Sentence case headings. Straight quotes, not curly.

## Facts and claims

Sales copy and playbook content only use claims that can be checked against `index.html` or a
client's own numbers. Do not invent case studies, statistics, client names, or credentials. When
proof is thin, say so in the document rather than filling the gap.

Two standing facts to protect:

- Red Flame Gas gets around five new customers a day from local search. That is one client's
  number, not an average across clients.
- There are two named clients, both gas businesses. We have no external credentials, awards, or
  press.

## Sales playbook

`docs/SALES-PLAYBOOK.md` is a living document for the sales course revision. Each module is
appended, the table of contents and the "last updated" line at the bottom are updated with it.
Modules so far: features and benefits, Cialdini's influence principles, the elevator pitch,
objection handling.

Modules 3 and 4 have had the humanizer pass. Modules 1 and 2 have not, so they still contain em
dashes and bold-label lists.

The five pitches in Module 3 are timed against stated word counts. Changing their wording changes
the timings, so recount and retime whenever one is edited.

## Git

Work happens on `claude/clarity-clicks-features-benefits-12eo0f`. Commit and push when a module
or a change is complete.
