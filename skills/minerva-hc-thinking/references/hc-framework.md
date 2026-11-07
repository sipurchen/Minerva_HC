<!-- ── SipurCodex BEGIN: public-source framework / 公開來源框架 ── -->
# HC Framework for Applied Work

## Source boundary

Minerva University publicly describes:

- **Habits of Mind** as cognitive skills that can become automatically triggered through practice.
- **Foundational Concepts** as broadly applicable knowledge that usually requires deliberation.
- Four core competencies: thinking critically, thinking creatively, communicating effectively, and interacting effectively.
- Repeated application across disciplines, behavioral rubrics, and transfer to new contexts.

Primary sources:

- [An Introduction to Habits of Mind and Foundational Concepts](https://www.minerva.edu/public/media/enrollment-center/Minerva-HCs-Intro.pdf)
- [Minerva Four-Year Curriculum](https://www.minerva.edu/four-year-curriculum/)

The public documents have changed across years and do not establish one stable, current, complete public HC catalog. The operational tools below are a narrow adaptation from public examples and competency descriptions. They are not official Minerva rubrics.

## Habit selection map

### Thinking critically

| Tag | Reach for it when | Required artifact | Misuse to avoid |
| --- | --- | --- | --- |
| #estimation | A numeric claim may be implausible | Range, units, assumptions, order-of-magnitude check | Treating a rough estimate as a measured value |
| #induction | Limited observations support several explanations | At least two plausible generalizations and one discriminator | Treating a pattern as proof |
| #sourcequality | A decision depends on documents, testimony, or generated content | Source, date, proximity, incentive, corroboration ledger | Ranking sources only by authority or popularity |
| #decisiontradeoffs | Several options affect different stakeholders | Cost, benefit, risk, reversibility, and stakeholder matrix | Hiding value judgments inside a numeric score |

### Thinking creatively

| Tag | Reach for it when | Required artifact | Misuse to avoid |
| --- | --- | --- | --- |
| #modeltypes | The team is confusing the real system with a representation | Model type, purpose, included variables, excluded variables | Optimizing the model instead of the real outcome |
| #constraints | A problem has hard limits or competing requirements | Hard, soft, assumed, and testable constraints | Treating a preference as an immutable constraint |
| #breakitdown | The task is too large to execute or verify | Components, dependencies, interfaces, stopping conditions | Splitting work without preserving the system goal |
| #designthinking | A solution needs iteration with users or evidence | Problem, prototype, test, result, revision log | Calling one untested draft a prototype cycle |

### Communicating effectively

| Tag | Reach for it when | Required artifact | Misuse to avoid |
| --- | --- | --- | --- |
| #composition | The message is vague, long, or structurally confusing | Audience, purpose, claim, support, action | Removing necessary qualification in the name of brevity |
| #multimodaldesign | Meaning depends on text, visual, audio, or interaction | Channel-role map and perception/accessibility check | Repeating identical content in every channel |

### Interacting effectively

| Tag | Reach for it when | Required artifact | Misuse to avoid |
| --- | --- | --- | --- |
| #stakeholders | People bear different costs, benefits, or authority | Stakeholder, interest, influence, impact, voice map | Treating the loudest person as the only stakeholder |
| #negotiate | Parties have shared and conflicting interests | Interests, priorities, process, concessions, walk-away condition | Bargaining positions without identifying interests |
| #differences | A team needs complementary skills or perspectives | Capability map, role fit, decision rights, missing voice | Stereotyping people from group identity |
| #ethicaleffects | A technically valid choice may shift harm or opportunity | Affected groups, benefits, harms, uncertainty, mitigation | Treating compliance as the whole ethical analysis |

## Application protocol

For each selected habit:

1. Name the decision or artifact it will change.
2. Ask one forcing question.
3. Produce one visible artifact.
4. State what changed after applying it.
5. Remove the tag if nothing changed.

## Alignment with stage-based decision frameworks

<!-- ── SipurCC BEGIN: stage-framework alignment addition / 階段式框架對應新增 ── -->
When this Skill is used alongside a separate stage-based reasoning discipline (for example, a framing/evidence/decision-points/plan/verification style sequence), habits slot naturally into specific stages rather than being applied all at once:

| Stage-type | Habits that typically apply there |
| --- | --- |
| Framing the problem | #constraints, #breakitdown |
| Gathering and checking evidence | #sourcequality, #estimation, #induction |
| Naming real decision points | #decisiontradeoffs, #modeltypes, #stakeholders |
| Planning or designing a response | #designthinking, #composition, #multimodaldesign |
| Verifying or reviewing the result | #ethicaleffects, #negotiate, #differences |

This is a starting map, not a rule: a habit that changes the output at an unlisted stage should still be used there, and a listed habit that would not change anything at that stage should still be dropped per the stand-down gate. Do not force every stage of an external framework to carry a habit tag.
<!-- ── SipurCC END ── -->

## Cross-domain transfer task

A transfer task changes the surface domain while preserving the cognitive operation.

Example structure:

- **First context:** use #constraints to design a low-memory media pipeline.
- **Second context:** use #constraints to design a 45-minute lesson.
- **Transfer prompt:** Which constraints are hard, soft, assumed, or testable in both cases?
- **Evidence of transfer:** the learner independently produces both constraint tables and explains what stays invariant.

Do not call a near-duplicate exercise transfer. Changing only names, numbers, or visual theme is repetition, not a new context.

## Adapted behavioral rubric

| Level | Observable behavior |
| --- | --- |
| 1 — Recognition | Names a habit but does not use it to change an artifact or decision. |
| 2 — Guided application | Applies the habit with prompts; misses a material assumption, stakeholder, or check. |
| 3 — Independent application | Correctly applies the habit in a familiar context and produces the required artifact. |
| 4 — Transfer | Independently applies the habit in a meaningfully different context and explains the invariant operation. |
| 5 — Integration | Selects and combines habits appropriately, tests limitations, revises the result, and can coach another learner with evidence. |

Scores require cited behavior. Do not infer mastery from confidence, fluent language, or one correct answer.

## Course-design pattern

Use three stages:

1. **Introduce:** model one habit and its artifact.
2. **Practice and transfer:** repeat it in two unrelated project domains with feedback.
3. **Integrate:** require learners to select habits, justify the selection, produce artifacts, and self-assess against the rubric.

Content is the practice medium. The learning target is the transferable behavior.

### Scaling the pattern to a multi-domain curriculum

<!-- ── SipurCC BEGIN: multi-domain scaling addition / 多領域擴充新增 ── -->
The same three stages scale from one lesson to a full curriculum without changing their shape:

- **Foundation tier:** one short unit per habit family (critical, creative, communication, interaction), each introducing only the habits that will be reused later, plus how to read the rubric. Keep this tier small — its job is vocabulary and one worked example per habit, not mastery.
- **Applied tier:** several unrelated subject-matter units, each required to select 2–4 habits from the foundation tier and produce the matching artifacts. Reusing the same small habit set across domains the learner did not expect to connect is what produces transfer evidence; introducing new habits in this tier dilutes it.
- **Capstone tier:** learners choose an unfamiliar problem and select their own habits without being told which ones apply, at Level 4–5 of the rubric. A capstone that supplies the habit list for them only tests Level 2–3 application.

A curriculum that keeps growing the foundation tier instead of reusing it across the applied tier is a sign the design has drifted from "shared transferable habits" back toward "one new framework per topic" — the exact pattern this Skill exists to avoid.
<!-- ── SipurCC END ── -->

<!-- ── SipurCodex END ── -->
