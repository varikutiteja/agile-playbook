# Definition of Done

A shared agreement across the team on what "done" actually means.
Without this, every engineer has a different definition — and quality suffers.

---

## Why this matters

> "Done means nothing if everyone defines it differently."

At VIGIT TECH, establishing a clear Definition of Done reduced
rework by eliminating assumptions between PM, engineering, and QA.

---

## Code complete checklist

- [ ] Feature works as described in acceptance criteria
- [ ] Code reviewed by at least one other engineer
- [ ] No new bugs introduced
- [ ] Edge cases handled and tested
- [ ] Error messages are user friendly

---

## Testing checklist

- [ ] Unit tests written and passing
- [ ] Integration tests passing
- [ ] Tested on all required browsers / devices
- [ ] QA sign off received
- [ ] No critical or high severity bugs open

---

## Documentation checklist

- [ ] Code is commented where necessary
- [ ] API documentation updated if endpoints changed
- [ ] README updated if setup steps changed
- [ ] Release notes written

---

## Deployment checklist

- [ ] Feature flag configured if required
- [ ] Deployed to staging and verified
- [ ] Product Manager has reviewed and approved
- [ ] Stakeholders notified of release
- [ ] Monitoring and alerts configured

---

## Definition of Done by story type

| Story type | Extra requirements |
|---|---|
| New feature | Full QA sign off, PM approval, release notes |
| Bug fix | Root cause documented, regression test added |
| Tech debt | Code review by senior engineer, no performance regression |
| Compliance | Legal review completed, audit log updated |

---

## The PM's role in Done

- Never mark something done without QA sign off
- Always verify against acceptance criteria personally
- Communicate to stakeholders when items are live
- Document any scope changes made during development