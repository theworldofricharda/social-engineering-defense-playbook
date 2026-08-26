# 05 — A Guide for Non-Security Staff

## Start here if security isn't your job title

If you work in accounting, HR, front desk, warehouse operations, customer support, or basically anywhere that isn't "IT" or "security," this section is written for you specifically, and it's worth reading in full even if security training usually feels irrelevant to your actual job. Here's why it isn't: in every case study in this project, the person who was targeted first was never someone in the security department. It was a refrigeration contractor's employee, a general support technician, a help desk staffer doing exactly what their job description asked of them. You are not a bystander to security. In most real breaches, you're the actual front line, whether anyone told you that or not.

## The one rule that covers almost everything below

**If a request is urgent, unusual, or asks you to bypass a normal step, verify it through a channel the requester doesn't control, before you act.**

That's it. That's the rule that would have stopped Target, Twitter, Uber, and MGM/Caesars, in four completely different industries, using four completely different techniques. Not "be more careful." Not "don't click links." Just: when something feels engineered to make you move fast, that's exactly the moment to slow down and check through a separate path.

## What this looks like by channel

**A phone call from "IT" asking you to reset something or provide a code.** Hang up. Call IT back using the number in the company directory, not a number the caller gave you or that showed up on caller ID. This single habit is what would have stopped the MGM and Caesars breaches. A legitimate IT department will never be upset that you verified independently; an attacker will never willingly wait for you to do it.

**An email from an executive asking for an urgent, unusual action** (a wire transfer, a gift card purchase, sending sensitive files). Executives who are actually in a hurry are still reachable through a second channel: a phone call, a Slack/Teams message, walking to their office. If the request only exists in an email and insists on speed and secrecy, that combination of features is itself the red flag, regardless of how convincing the writing sounds.

**A text message claiming to be from your company's IT or HR system.** Treat it with the same suspicion as an email, not less. People are demonstrably more trusting of text messages than emails, which is exactly why attackers have shifted toward SMS-based phishing (smishing) in several of the largest breaches in this project. Never enter your company credentials into a page you reached by tapping a link in a text.

**Someone following you through a secure door without badging in.** It feels rude to challenge a stranger, especially one who seems confident and busy. Challenge them anyway, or direct them to the front desk. A legitimate visitor or new employee will not be offended by this. An attacker relying on your politeness is counting on exactly the discomfort you're feeling right now.

**A "found" USB drive, or an unsolicited offer of free software, a scan, or IT help you didn't request.** Don't plug it in, don't install it, don't accept help you didn't ask for. Hand a found drive to IT and let them handle it in an isolated way.

## Why the "verify separately" rule works even when you can't spot the trick

You are not expected to be able to identify every fake login page, every spoofed phone number, or every well-researched pretext. Nobody can, reliably, under time pressure, indefinitely. That's not a personal failing; it's the entire reason social engineering exists as a technique instead of having died out decades ago. What you can reliably do is notice when a request wants an answer *now*, through *this one channel*, without you checking anywhere else. That pattern is detectable even when the specific fake email or fake caller is not.

## What to do if you think you already made a mistake

Report it immediately, to IT or security, using whatever the fastest reporting path is at your organization. Do not wait to be sure. Do not worry about looking foolish. Every case study in this project had a window of time between the initial compromise and the serious damage, sometimes hours, sometimes weeks, during which fast reporting could have limited or stopped the escalation entirely. The single costliest thing you can do after a mistake is stay quiet about it out of embarrassment. Nobody in any of these case studies was fired for reporting a mistake quickly. Real damage happened when mistakes went unreported.

## Why the "annoying" security requirements at your company exist

The multi-factor authentication prompt that takes an extra ten seconds. The rule that IT will never ask for your password over the phone. The requirement to badge in even when someone's holding the door. None of these exist because your security team doesn't trust you personally. They exist because every single organization in this project had smart, careful, well-intentioned employees, and every single one of them was still successfully targeted. The friction is not a judgment about you. It's the actual thing standing between an ordinary phone call and a company-wide breach, and in at least one case in this project, the presence or absence of exactly this kind of friction (a hardware security key versus a plain password) was the entire difference between a company that stayed secure and several others that didn't, during the identical attack campaign.

---
**Previous:** [← 04 — Defensive Measures](../04-defensive-measures/README.md)
**Next:** [06 — Diagrams & Data →](../06-diagrams-and-data/README.md)
