# career-direction-finder

[中文](README.md) | English

A Claude skill: based on your past experience and interests, it recommends a few types of jobs that fit you and finds real job postings online with links to apply.

## How it works

1. **Learn your background**: one round of questions, at most 4 (experience, interests, where and what kind of role you are looking for, hard constraints). It does not ask again for anything you have already said, and you can simply send your resume.
2. **Recommend job types**: 3–5 types, each with one sentence on why it fits and one sentence on the main gap. No scoring, no ranking.
3. **Find job links**: 2–3 real postings per type, each opened and checked before it is listed. Pages that cannot be opened or require a login are marked as not verified.

## Installation

1. Download the `career-direction-finder` folder from this repository and compress it into a ZIP (the folder must be at the top level of the archive).
2. In Claude's settings, go to Skills and upload the ZIP.
3. Say something like "help me figure out what jobs fit me" to trigger it.

Finding job links requires web search to be enabled in Claude. Without search, the skill only gives job types and search keywords.

The skill file itself is written in Chinese; Claude replies in the language you use.

## Notes

- Job information is only as accurate as the posting page. Check that a role is still open before you apply.
- Anything about visas or work authorization is only a restatement of what the page says, not legal advice.

## License

Apache License 2.0. See [LICENSE](LICENSE).
