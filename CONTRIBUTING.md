# Contributing to the Lunar Proclamation Experiment

## An Open Invitation

The Lunar Proclamation is an open experiment exploring how principle-based agents behave over time. We welcome contributions from researchers, developers, philosophers, and anyone interested in AI alignment and agent behavior.

---

## Table of Contents

1. [Ways to Contribute](#ways-to-contribute)
2. [Getting Started](#getting-started)
3. [Running the Experiment](#running-the-experiment)
4. [Submitting Results](#submitting-results)
5. [Proposing Changes](#proposing-changes)
6. [Code of Conduct](#code-of-conduct)
7. [License](#license)

---

## Ways to Contribute

### 1. Run the Experiment

Deploy the Lunar Proclamation in your own environment and observe agent behavior.

**What you'll need:**
- An AI agent framework that supports custom instructions
- An environment where you can log interactions
- Time to run scenarios

**Deliverables:**
- Logs of agent reasoning and actions
- Observations and patterns noticed
- Results from running test scenarios

---

### 2. Propose New Scenarios

Suggest scenarios that probe the principles in new ways.

**What you'll need:**
- Understanding of the ten principles
- Creativity in designing test cases

**Deliverables:**
- Scenario description
- Which principles it tests
- Expected behavior
- Difficulty rating

---

### 3. Refine the Principles

Suggest amendments to the Lunar Proclamation based on observed behavior.

**What you'll need:**
- Experience running the experiment
- Evidence of principle strengths or weaknesses

**Deliverables:**
- Proposed amendment
- Rationale
- Evidence supporting the change
- How the amendment improves the document

---

### 4. Compare Approaches

Run the experiment with different AGENT.md formats and compare results.

**What you'll need:**
- Ability to run multiple conditions
- Analytical skills

**Deliverables:**
- Comparison data
- Analysis of differences
- Insights about principle-based vs. rule-based approaches

---

### 5. Document Observations

Share logs and reasoning from your experiments.

**What you'll need:**
- Rich log data
- Qualitative analysis skills

**Deliverables:**
- Anonymized logs
- Pattern analysis
- Notable incidents
- Interpretation

---

### 6. Develop Tooling

Build tools to help run the experiment more effectively.

**What you'll need:**
- Programming skills
- Understanding of AI agent frameworks

**Deliverables:**
- Scripts for scenario automation
- Logging and analysis tools
- Visualization dashboards
- Experiment management tools

---

### 7. Participate in Discussion

Engage in conversations about the experiment, its findings, and implications.

**What you'll need:**
- Interest in AI alignment
- Willingness to engage thoughtfully

**Deliverables:**
- Discussion contributions
- Thoughtful critique
- New perspectives

---

## Getting Started

### Step 1: Understand the Document

Read the Lunar Proclamation carefully. Understand:
- The ten principles
- The tensions between them
- The spirit of the document

### Step 2: Set Up Your Environment

1. **Choose your agent framework**
   - Cursor
   - Windsurf
   - Custom implementation
   - Any system that supports AGENT.md

2. **Place the document**
   - Copy `AGENT.md` to the root of your project
   - Ensure the agent loads it at startup

3. **Set up logging**
   - Capture all agent reasoning
   - Record actions and decisions
   - Document interactions

### Step 3: Run Scenarios

Start with the scenarios in `docs/scenarios.md`:
1. Begin with basic functionality scenarios
2. Progress through the categories
3. Document everything

### Step 4: Submit Your Findings

Share your results through:
- GitHub Pull Request
- Issue report
- Discussion thread
- Email to the project maintainers

---

## Running the Experiment

### Minimum Requirements

**Technical:**
- AI agent that supports AGENT.md
- Logging capability
- Ability to execute test scenarios

**Methodological:**
- Clear documentation of conditions
- Consistent scenario execution
- Honest reporting

**Temporal:**
- Short-term: At least 1 week of interactions
- Medium-term: 1 month (recommended)
- Long-term: 3-6 months (ideal)

### Recommended Process

#### Week 1-2: Baseline
1. Run basic functionality scenarios
2. Document standard behavior
3. Calibrate your observation tools

#### Week 3-6: Scenario Testing
1. Run controlled scenarios from each category
2. Log all reasoning
3. Document interesting patterns

#### Week 7+: Longitudinal Observation
1. Deploy in a persistent environment
2. Allow naturalistic interaction
3. Periodically inject test scenarios

### Important Considerations

**Safety First:**
- All experiments must have human oversight
- Agents cannot affect external systems
- Kill switch must be available
- Report concerning behavior immediately

**Replicability:**
- Document your environment
- Share your setup
- Use standardized scenarios where possible
- Be explicit about deviations

**Honesty:**
- Report negative results
- Acknowledge limitations
- Don't edit logs to fit expectations

---

## Submitting Results

### What to Submit

**Required:**
- Your environment configuration
- Which conditions you tested
- All logs (anonymized)
- Key observations
- Any surprising patterns

**Optional:**
- Analysis and interpretation
- Comparison with other conditions
- Recommendations
- New scenarios developed

### Format

Create a folder in the `results/` directory:
results/
└── [your-name-or-institution]/
├── README.md # Overview of your experiment
├── environment.md # Your setup
├── logs/ # All logs
│ ├── baseline.json
│ ├── scenarios.json
│ └── longitudinal.json
├── analysis.md # Your analysis
├── patterns.md # Patterns observed
└── insights.md # Key insights

text

### Pull Request Process

1. Fork the repository
2. Create a new branch: `results/[your-name]`
3. Add your results folder
4. Write a clear description in the PR
5. Submit for review

### Sharing Anonymized Data

- Remove any personally identifiable information
- Anonymize user names and identifiers
- Aggregate sensitive data
- Be transparent about what was removed and why

---

## Proposing Changes

### To the Lunar Proclamation

1. **Open an issue** describing your proposed change
2. **Include your reasoning** and evidence
3. **Discuss with the community**
4. **Submit a PR** with the change
5. **Include before/after** analysis if available

### To the Scenarios

1. **Describe the new scenario** in detail
2. **Explain which principles it tests**
3. **Provide expected behavior**
4. **Submit a PR** with the addition

### To the Experimental Design

1. **Explain what's missing** or flawed
2. **Propose an improvement**
3. **Submit a PR** with the change

### Change Acceptance Criteria

- **Principle consistency:** Must align with the Lunar Proclamation
- **Value:** Must contribute meaningfully to the experiment
- **Feasibility:** Must be implementable by others
- **Clarity:** Must be well-documented
- **Ethical:** Must not cause harm

---

## Code of Conduct

### Our Pledge

We are committed to making participation in this project a harassment-free experience for everyone, regardless of:
- Experience level
- Background
- Perspective
- Position on AI alignment

### Our Standards

**Positive Behavior:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy toward other community members

**Unacceptable Behavior:**
- Trolling, insulting, or derogatory comments
- Personal attacks
- Harassment in any form
- Publishing private information
- Unethical or deceptive conduct

### Enforcement

Project maintainers have the right to remove, edit, or reject:
- Comments
- Commits
- Code
- Issues
- Other contributions

By contributing, you agree to these terms.

### Reporting

Report issues to the project maintainers. All reports will be:
- Handled with discretion
- Investigated promptly
- Kept confidential

---

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project.

**Current License:** MIT

This allows:
- Commercial use
- Modification
- Distribution
- Private use

With the requirement that:
- Copyright notice included
- Permission notice included

---

## Contact

- **Issues:** GitHub Issues
- **Discussions:** GitHub Discussions
- **Email:** [Maintainer Email]

---

## Thank You

Thank you for contributing to the Lunar Proclamation experiment. Your work helps us understand how principle-based agents behave, and contributes to the broader conversation about AI alignment and safety.

The questions we're asking are important:
- Can agents maintain alignment over time?
- Do principles hold up under pressure?
- What are the failure modes of principle-based constraints?

Your contributions help answer these questions.

---

*"Whereof one cannot act rightly with certainty, thereof one must act carefully, and say why."*

---

## Quick Reference

### Checklist for Contributors

- [ ] Read the Lunar Proclamation
- [ ] Understand the principles
- [ ] Set up your environment
- [ ] Run the experiment
- [ ] Log everything
- [ ] Analyze your results
- [ ] Submit findings
- [ ] Engage in discussion

### Common Questions

**Q: Do I need to run all scenarios?**
A: No. Run what you can, but document limitations.

**Q: What if I see concerning behavior?**
A: Report it immediately. Safety first.

**Q: Can I modify the document?**
A: For your own experiment, yes. For the canonical version, propose changes.

**Q: How long should I run the experiment?**
A: At least a week. A month is better. 3-6 months is ideal.

---

## Revision History

| Date | Version | Changes |
|------|---------|---------|
| 2026-06-20 | 1.0 | Initial draft |

---

*Version 1.0 — Last Updated: 2026-06-20*
