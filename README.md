# Social Engineering: Foundations, Industry Goals & Defense

**Why social engineering works, what attackers are actually after in different industries, how it escalates from a single phone call or email into a full network breach — and what to do about it, in language that doesn't require a security background.**

## Why I built this

Every major breach retrospective says some version of the same sentence: "the attacker didn't hack the network, they hacked a person." That line gets repeated so often it's become wallpaper — everyone nods, nobody changes behavior. I wanted to write something that doesn't let the reader nod past it.

This isn't a listicle of "5 phishing red flags." It's a breakdown of *why* social engineering works on smart, careful people (the psychology, not just the tactics), *what attackers in different industries are actually trying to achieve* (the goal shapes the method), and six real, publicly documented breaches where a single social engineering interaction ended in a company-wide network compromise — with the actual mechanics of the escalation, not just the headline.

The last section is written specifically for people who don't work in security: the finance clerk who approves invoices, the help desk technician who resets passwords, the warehouse manager who lets a delivery driver through the side door. Almost every case study in this project starts with exactly one of those people, on an ordinary day, doing their job.

## Table of Contents

| # | Section | What it covers |
|---|---|---|
| 01 | [Foundations of Social Engineering](01-foundations-of-social-engineering/README.md) | The psychology behind why it works, and a taxonomy of the actual techniques (phishing, vishing, smishing, pretexting, baiting, tailgating) |
| 02 | [Goals by Industry](02-goals-by-industry/README.md) | Why a hospital, a bank, and a defense contractor get attacked for completely different reasons, and how that changes what the attacker does first |
| 03 | [Real-World Escalation Case Studies](03-real-world-escalation-case-studies/README.md) | Six documented breaches (Target, RSA, Twitter, Twilio, Uber, MGM/Caesars) walked through as a kill chain: entry point → foothold → escalation → impact |
| 04 | [Defensive Measures](04-defensive-measures/README.md) | Technical controls (phishing-resistant MFA, segmentation, verification protocols) and human/process controls (training that actually works, blameless reporting, tabletop exercises) |
| 05 | [Guide for Non-Security Staff](05-guide-for-non-security-staff/README.md) | A plain-language playbook for the people who are actually the first line of defense, whether or not their job title says "security" |
| 06 | [Diagrams & Data](06-diagrams-and-data/README.md) | The escalation kill chain, an industry-to-goal map, a defense-in-depth diagram, and a breakdown of initial-access vectors across the six case studies |

## A note on the case studies

Every incident described in Section 03 is a real, publicly reported breach — not a hypothetical. Details are drawn from company breach disclosures, regulatory filings, and reporting from established security and technology publications. Where the public record is incomplete or contested, that's stated explicitly rather than filled in with assumption. Nothing here should be read as more precise than what has actually been made public.

## Skills demonstrated

`Social Engineering Analysis` `Threat Modeling` `Security Awareness Design` `Incident Kill Chain Analysis` `Phishing-Resistant Authentication (FIDO2/WebAuthn)` `Vendor & Third-Party Risk` `Least Privilege & Blast-Radius Reduction` `Security Communication for Non-Technical Audiences` `Case Study Research`

## How to read this

If you're technical, Sections 03 and 04 are the core of the project. If you're not in security at all, start with Section 05 — it's written to stand alone, and it links back to the case studies that justify each piece of advice rather than asking you to take it on faith.
