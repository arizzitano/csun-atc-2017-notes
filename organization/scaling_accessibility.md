# Scaling Accessibility

3/1/2017
Dylan Barrell, Deque Systems

## Organizations
- Reactive (dealing with external pressure towards a11y)
- Proactive (internal motivation to make a11y stick)

### Proactive orgs
- a11y is a business requirement
- part of development process, all cycles
- Requirements: either external standard (WCAG2AA etc) or homegrown
- All contributors trained on a11y (SR, standards, dev tools, etc)
- a11y issues typically rot in backlog :(

### Reactive orgs
- Deal with external deadlines
- Embed experts in teams to make sure devs are doing the right thing
- It me
- High motivation but drops off after deadline

## Problems
- a11y overwhelming (manual testing etc)
- Usability problem as well as technical problem
- Need experts in all depts

## Sustainable Accessibility
- Stop expecting magic
- Set achievable goals
- End goal: integrate a11y into all aspects of dev process starting with UX

### UX
- Personas
- User research
- Design solutions to be accessible from the beginning
- Designs must be annotated/interaction notes
- Specify ROLE, NAME, STATE
- Call out mouse AND keyboard interactions
- How do we make UX designers do all this?

### Dev
- Lots of automated testing
- Generic automated testing: aXe
- Acceptance automation: test components against UX requirements
- Manual testing during development: keyboard, screen reader
- PRIORITIZE FIXING DEFECTS
- Need clear designation for issue priority
- Stop ship for critical issues

## Realistic goals
- Start with subset of wcag2aa
- Teams need time to achieve
- Increase subset over time
- Allow teams to self-serve and achieve more if they want to

## Stop expecting magic
- Explicit communication: process, end goal, progress
- Become an enabler
- Access to the best tools for automated and manual testing
- PATTERN LIBRARIES AND EXAMPLES
- Review UX work
- Help when struggling
- Find everything that can be found with automation
- 30-50% of issues can be found by aXe
