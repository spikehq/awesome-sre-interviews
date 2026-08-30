# Awesome SRE Interviews [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A community-curated bank of real SRE, DevOps, and incident-response interview questions and experiences — built by the people who've sat in the interview chair.

Most prep guides give you a generic reading list. This one is a living, contributed record of what companies are actually asking, and what it's like to answer.

## Contents

- [How to Use This List](#how-to-use-this-list)
- [System Design Scenarios](#system-design-scenarios)
- [Incident Response & RCA Questions](#incident-response--rca-questions)
- [Behavioral Questions](#behavioral-questions)
- [Technical & Troubleshooting Questions](#technical--troubleshooting-questions)
- [Real Interview Experiences](#real-interview-experiences)
- [Prep Resources](#prep-resources)
- [Contributing](#contributing)

## How to Use This List

Each question is a starting point, not a script — interviewers want to see how you think, not a memorized answer. If you've been asked something that isn't here, or you want to share how an interview actually went, see [Contributing](#contributing).

## System Design Scenarios

- Design an on-call rotation and escalation system for a 200-engineer org across 3 time zones.
- Design an alerting pipeline that minimizes alert fatigue while still catching real incidents.
- Design a status page system that updates automatically from your monitoring stack.
- How would you design a system to page the right team automatically, given an ambiguous root cause?
- Walk through how you'd design a postmortem/RCA tracking system that prevents recurring incidents from going unnoticed.

## Incident Response & RCA Questions

- Walk me through your ideal incident response process, from alert to resolution.
- How do you decide incident severity, and who gets to change it?
- Tell me about a time you led an incident. What went well, what didn't?
- How do you run a blameless postmortem when the root cause is a specific person's mistake?
- What's the difference between a root cause and a contributing factor, and why does the distinction matter?
- How do you handle an incident where the root cause is still unknown after mitigation?

## Behavioral Questions

- Describe a time you disagreed with an on-call escalation decision. What did you do?
- How do you balance on-call load fairly across a team with mixed seniority?
- Tell me about a time you had to communicate an ongoing incident to non-technical stakeholders.
- How do you handle burnout on a team with heavy on-call load?
- Describe a time you pushed back on being paged for something that shouldn't have paged.

## Technical & Troubleshooting Questions

- A service's p99 latency spikes every day at the same time. How do you investigate?
- Walk through how you'd debug a service that's returning 502s intermittently.
- Explain what happens between typing a URL and a page loading, focusing on where things can fail.
- How would you troubleshoot a Kubernetes pod stuck in `CrashLoopBackOff`?
- Write a script (any language) to parse a log file and alert if error rate exceeds a threshold in a rolling window.
- Explain the difference between a liveness probe and a readiness probe, and what happens if you misconfigure one.

## Real Interview Experiences

*This section is community-contributed. Company names are optional — anonymize freely.*

_No entries yet — be the first to add yours. See [Contributing](#contributing)._

## Prep Resources

- [Site Reliability Engineering](https://sre.google/books/) - Google's SRE book (free online).
- [The Site Reliability Workbook](https://sre.google/books/) - Practical companion to the SRE book.
- *Seeking SRE*, edited by David N. Blank-Edelman (O'Reilly).
- [mxssl/sre-interview-prep-guide](https://github.com/mxssl/sre-interview-prep-guide) - Broader SRE interview prep guide and reading list.

## Contributing

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Real interview experiences are the heart of this list: add a question you were asked, or a short writeup of how the interview went. Anonymize company/interviewer names if you'd rather not disclose them.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work. See [LICENSE](LICENSE).
