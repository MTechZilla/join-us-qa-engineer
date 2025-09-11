# Join Us

This assignment is designed for the Senior QA Engineer role at MTechZilla. You’ll evaluate a real SaaS-style demo. Treat it like a production app and demonstrate how you think, plan, test, automate, communicate, and leverage AI.

Target under test: https://nextjs-supabase-ai-template-demo.vercel.app/en

Timebox: Complete within 24 hours of starting. Document what you deliberately skipped and why.

Ground rules: Test with dummy data only. Be responsible and non-destructive. Passive security checks only.

## What We Measure

1. Prioritization under constraint – where you invest limited time and why
2. Depth of insight – bugs + root cause hypotheses + business/user impact
3. Creativity – boundary/edge cases, adversarial thinking (esp. AI features)
4. Communication – crisp strategy, actionable bugs, clear recommendations
5. AI fluency – uses AI to accelerate (not replace) QA judgment

## Core Deliverables

### Strategy & Priorities (1 page)
Deliver:
* Top 5 risks for this app (business, user, tech) with rationale
* Test scope and explicit out-of-scope items with trade-off reasoning
* First 90 minutes plan – what you'll test first and why
* 3 critical questions you'd ask PM/Engineering before testing

### Exploratory Testing
* Auth & session management
* AI feature behavior & safety (prompt injection, limits, error handling)
* Data integrity & CRUD operations
* Payment flows – use Stripe test environment
  * Primary test card: 4242 4242 4242 4242 (use any future expiry date + any CVC)
  * Reference: Stripe Test Cards (https://docs.stripe.com/testing) for additional scenarios (declines, authentication, etc.)
* Cross-browser/device compatibility
* Accessibility (WCAG 2.2 A/AA spot check)
* Performance (perceived + Web Vitals)

For each session, document:
* Finding summary with severity (P1-P4) and user/business impact
* Evidence (screenshots/console logs) for critical issues only
* Reproduction steps for P1/P2 bugs

Then create:
* Top Issues List – critical findings across both sessions
* Go/No-Go recommendation with confidence level (High/Medium/Low) and one-line justification

### Deep Dive Analysis
* Performance bottlenecks – Core Web Vitals analysis with specific optimizations
* Accessibility barriers – Critical WCAG violations with remediation

Deliver a brief analysis:
* Problem statement
* Top 3 findings with evidence
* Business/user impact
* Concrete fix recommendations

### AI-Assisted Testing Log
Document how you used AI tools:
* 2-3 example prompts that accelerated your testing
* What AI suggestions you accepted vs. rejected and why
* Privacy precautions taken (no production data, sanitized URLs, etc.)

## Submission Format
Required Files (all in single PDF):
* Strategy document
* Testing notes with findings from both exploratory sessions
* Top Issues table with columns: Issue | Severity | Impact | Recommended Fix
* Deep dive analysis
* AI usage examples

## Optional but Valuable:
* 3-5 min video walkthrough of your most interesting findings (Loom or similar)
* Link to a simple spreadsheet if you prefer tabular format for issues

Submit to: jobs@mtechzilla.com

Subject: "Senior QA Assessment – [Your Name]"

## Evaluation Rubric (100 pts)
* Impact & insight (root causes, business implications) – 35
* Strategic prioritization (what to test/skip decisions) – 25
* Test creativity (edge cases, exploratory skills) – 20
* Clear communication – 10
* Effective AI usage – 10

Bonus signals: Quality of clarifying questions, realistic Go/No-Go assessment, explicit "what I didn't test and why"

The timeline to complete this test is a maximum of one day.
