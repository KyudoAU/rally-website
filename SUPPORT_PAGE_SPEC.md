# Rally Support Page — UX Specification

## Overview

The Support page serves as Rally's self-service help centre, reducing support burden while providing a warm, accessible experience for users who need assistance. It should feel like a helpful friend guiding you through the app — not a corporate knowledge base.

**URL:** `/support` or `/support.html`  
**Target users:** Organisers (primary) and Helpers (secondary)  
**Primary goal:** Self-service resolution of common issues  
**Secondary goal:** Easy escalation path when self-service isn't enough

---

## Page Structure

### 1. Header/Navigation
- Sticky nav consistent with homepage
- Logo links home
- Simple "Contact us" link in nav (mailto or anchor to contact section)
- No heavy nav links — this is a destination page, not a browsing page

### 2. Hero Section

**Headline:** "Support Centre" or "We're here to help"  
**Subhead:** "Answers to common questions about using Rally"  
**Icon:** 💚 (brand heart) or 🤝 (helping hands)

**Design notes:**
- Lighter gradient background (cream → pale green) — same palette as homepage
- Centred, warm, approachable
- No search bar in hero (FAQ is short enough to scan)

### 3. Quick Links (Optional — Mobile Enhancement)

On mobile, consider adding jump links to FAQ sections:
- Getting started
- Tasks & helpers
- Account & privacy
- Rally Pro

Helps mobile users skip to relevant content without scrolling.

### 4. FAQ Sections

Organised by user journey/topic. Each section has:
- Section heading (h2)
- Individual Q&A items (h3 question, p answer)

**Section structure recommendations:**

#### Section A: Getting started
For new users figuring out what Rally is and how to begin.

#### Section B: Tasks & helpers
Core app functionality — the most common operational questions.

#### Section C: Notifications & calendar
Technical features that often cause confusion.

#### Section D: Account & privacy
Login, data, and account management.

#### Section E: Rally Pro (subscription)
Pricing, features, billing, cancellation.

#### Section F: Troubleshooting
Common technical issues (added section — see FAQ recommendations below).

### 5. Contact Box (CTA)

Positioned at bottom of FAQ content.

**Headline:** "Still need help?"  
**Body:** "We're a small team and we read every message. Drop us an email and we'll get back to you within 24 hours."  
**CTA button:** "📧 Email us at hello@rally-around.us"

**Design:**
- Dark green background (brand `--green-dark`)
- White text
- Full-width rounded card
- Prominent but not aggressive

### 6. Footer
Standard site footer — links to Home, Privacy, Terms.

---

## FAQ Content Recommendations

Below are recommended questions and answers. Tone is warm, direct, and jargon-free.

### Getting started

**Q: What is Rally?**  
A: Rally is a care coordination app that helps you organise support for someone in need. An Organiser creates a "circle" and adds tasks, then invites helpers to claim what they can do. It removes the chaos of group chats and duplicated messages.

**Q: How do I create a circle?**  
A: After signing in, tap "Create Circle" on your dashboard. Give your circle a name, choose the situation type, add a description, then start adding tasks. Share the invite link with anyone you want to help.

**Q: How do I join a circle as a helper?**  
A: The organiser will share an invite link with you. Tap the link to open Rally, create a free account or sign in, and you'll be added to the circle automatically.

**Q: Is Rally free?**  
A: Yes — Rally is free for most people. The free plan includes 1 circle, up to 10 helpers, and up to 20 tasks. Rally Pro ($9/month) removes those limits for complex or ongoing situations.

**Q: What devices does Rally work on?**  
A: Rally is available for iPhone (iOS 14+) and Android (8.0+). Download from the App Store or Google Play.

---

### Tasks & helpers

**Q: How do I add a task?**  
A: From the Organiser dashboard, tap "+ Add Task". Choose a task type (meal, transport, errand, etc.), add a title, set the date and time, add location details if needed, and save.

**Q: Can I edit a task after creating it?**  
A: Yes. Tap any task on your dashboard to open the details, then tap "Edit Task" to make changes. Helpers will see the updated information.

**Q: What happens when a helper claims a task?**  
A: The task moves from "Open" to "Claimed" on your dashboard, and you'll receive a notification. The helper's name will be shown on the task so you always know who has committed.

**Q: Can a helper release a task they can no longer do?**  
A: Yes. Helpers can open the task and tap "Release task" to put it back in the open pool for someone else to claim. Life happens — no judgement.

**Q: How do I remove a helper from my circle?**  
A: Open your circle settings, go to "Members", find the helper, and tap "Remove". They'll no longer have access to the circle or its tasks.

**Q: Can I have multiple organisers for one circle?**  
A: Currently, each circle has one organiser. We're considering adding co-organiser support — let us know if this would help you!

---

### Notifications & calendar

**Q: How do I turn on push notifications?**  
A: Go to Settings in the app → Notifications → toggle on the notification types you want. Make sure notifications are also enabled for Rally in your phone's system settings (Settings → Apps → Rally → Notifications on iOS/Android).

**Q: I'm not receiving notifications. What should I check?**  
A: Three things to check:  
1. In-app: Settings → Notifications are enabled  
2. Phone settings: Rally app has notification permission  
3. Battery saver/Do Not Disturb isn't blocking them  

If notifications still don't arrive, try signing out and back in.

**Q: How does Google Calendar sync work?**  
A: When a helper claims a task, they can sync it to their Google Calendar. The task will appear as a calendar event with all the details. You'll need to grant Rally permission to create calendar events the first time you use this feature.

**Q: Can I sync tasks to Apple Calendar or Outlook?**  
A: Currently we support Google Calendar. Apple Calendar and Outlook sync are on our roadmap — contact us if this is important to you.

**Q: A task isn't showing in my calendar. Why?**  
A: Check that:  
1. You've connected Google Calendar in Rally settings  
2. The task has a date/time set  
3. You're looking at the correct Google account's calendar  

If it's still missing, try disconnecting and reconnecting your calendar in Settings.

---

### Account & privacy

**Q: How do I sign in?**  
A: Rally uses passwordless sign-in. Enter your email address and we'll send you a 6-digit code. Enter the code to sign in — no password to remember.

**Q: I'm not receiving the sign-in code. What should I do?**  
A: Check your spam/junk folder first. If it's not there:  
- Make sure you're checking the right email account  
- Wait 2 minutes and try again (codes can take a moment to arrive)  
- Check if your email provider is blocking rally-around.us  

Still stuck? Email us and we'll help sort it out.

**Q: Can I change my email address?**  
A: Yes. Go to Settings → Account → tap your email address to update it. We'll send a verification code to your new email.

**Q: Who can see my information?**  
A: Other circle members can see your display name and the tasks you've claimed or completed. Your email address is never visible to other users. We never sell your data.

**Q: Can I delete my account?**  
A: Yes. Go to Settings → scroll to the bottom → tap "Delete Account". This permanently deletes all your data including your profile, circles, and tasks. This action cannot be undone.

**Q: What happens to my data if I delete my account?**  
A: Everything is permanently deleted — your profile, any circles you organised, your membership in other circles, and all associated tasks. Helpers in your circles will see the circle has been closed.

---

### Rally Pro

**Q: What does Rally Pro include?**  
A: Rally Pro unlocks unlimited circles, unlimited helpers, and unlimited tasks. It also gives you early access to new features as we build them.

**Q: Who should get Rally Pro?**  
A: Rally Pro is designed for:  
- People coordinating ongoing or long-term care  
- Community groups managing multiple situations  
- Anyone who needs more than 1 circle, 10 helpers, or 20 tasks  

Most people do fine on the free plan.

**Q: How do I upgrade to Rally Pro?**  
A: In the app, go to Settings → Rally Pro → tap "Upgrade". Payment is handled through the App Store (iOS) or Google Play (Android).

**Q: How do I cancel my subscription?**  
A: Rally Pro subscriptions are managed through your device's app store.  
- **iPhone:** Settings → Apple ID → Subscriptions → Rally Pro → Cancel  
- **Android:** Play Store → Menu → Subscriptions → Rally → Cancel  

Your Pro access continues until the end of the current billing period.

**Q: Can I get a refund?**  
A: Refunds are handled by Apple or Google, not us directly. Contact Apple Support or Google Play Support to request a refund for your subscription.

---

### Troubleshooting

**Q: The app is crashing or freezing. What should I do?**  
A: Try these steps in order:  
1. Force-close the app and reopen it  
2. Check for app updates in the App Store / Google Play  
3. Restart your phone  
4. Uninstall and reinstall Rally  

If it's still crashing, email us with your phone model and what you were doing when it crashed.

**Q: My invite link isn't working.**  
A: Invite links expire after 7 days. If your link has expired, ask the organiser for a fresh one. If the link shows an error, the circle may have been closed.

**Q: I joined a circle but can't see any tasks.**  
A: The organiser may not have added tasks yet, or all tasks may already be claimed. Check with the organiser to confirm tasks are available.

**Q: How do I report a bug or give feedback?**  
A: We'd love to hear from you! Email us at hello@rally-around.us with details about what happened. Screenshots help.

---

## Contact Options

### Primary: Email
- **Address:** hello@rally-around.us
- **Response time:** Within 24 hours (business days)
- **Positioning:** "We're a small team and we read every message"

### Future considerations (not for v1):
- In-app feedback button (reduces friction)
- Contact form on website (captures structured info)
- Live chat (only if support volume justifies it)

### Response time expectations
Set realistic expectations. Small team = honest timelines.

**Recommended copy:**  
"We'll get back to you within 24 hours on business days. If you email on the weekend, we'll reply Monday."

---

## Search/Filtering

**Recommendation: Not needed for v1**

The FAQ is short enough (~20 questions) to scan without search. Adding search introduces complexity without proportional value at this stage.

**Future consideration:** If FAQ grows beyond 30-40 questions, consider:
- Client-side keyword search (simple JS filter)
- Category filters (show/hide sections)
- Algolia or similar (overkill unless FAQ becomes a full knowledge base)

---

## Mobile Responsiveness

### Breakpoints
- **Desktop:** Full layout (max-width ~780px for content)
- **Mobile (≤640px):** Single-column, stacked layout

### Mobile-specific considerations
1. **Touch targets:** FAQ headings should be tappable (44px minimum height)
2. **Section jump links:** Consider adding quick-nav to FAQ sections
3. **Contact button:** Full-width on mobile, sticky if below fold
4. **Footer links:** Stack vertically on mobile
5. **Font sizes:** Body at 15px minimum for readability

### Accordion vs. expanded
**Recommendation: Keep FAQ expanded (not accordion)**

Reasons:
- FAQ is short — accordion adds friction
- Search engines index expanded content better
- Users can CMD+F / CTRL+F to find keywords
- Simpler implementation

If FAQ grows significantly, reconsider accordion with expand-all option.

---

## Microcopy Recommendations

### Tone
- **Warm, not corporate.** "We'll get back to you" not "Your request has been received"
- **Direct.** Answer the question in the first sentence
- **Empathetic.** Acknowledge that users are often stressed when they need Rally
- **Casual where appropriate.** "Life happens — no judgement" works for Rally

### Examples

❌ "Please ensure your notification permissions are configured correctly in your device settings."  
✅ "Make sure notifications are turned on for Rally in your phone's settings."

❌ "In the event that your subscription requires cancellation..."  
✅ "To cancel your subscription..."

❌ "We apologise for any inconvenience this may have caused."  
✅ "Sorry about that — let us know and we'll help sort it out."

### Error states (for future contact form)
- **Empty field:** "Please enter your email"
- **Invalid email:** "That doesn't look like an email address"
- **Success:** "Message sent! We'll get back to you within 24 hours."
- **Error:** "Something went wrong. Try emailing us directly at hello@rally-around.us"

---

## Design Consistency

Reference existing Rally website styles:

### Colours
```css
--green:       #2D6A4F   /* Primary green */
--green-light: #3A8A6B   /* Light green */
--green-dark:  #1E4F3A   /* Dark green — footer, CTA box */
--cream:       #F9F5EF   /* Background tint */
--green-pale:  #E4F2EB   /* Section backgrounds */
--green-accent:#52B788   /* Checkmarks, highlights */
--text:        #1A1F1D   /* Body text */
--muted:       #6B7280   /* Secondary text */
--border:      #E0E8E4   /* Dividers */
```

### Typography
- **Font:** Inter (Google Fonts)
- **Headings:** 700-800 weight, `--green-dark` colour
- **Body:** 400-500 weight, `--text` or `--muted`
- **Section tags:** 12.5px, uppercase, letter-spacing 1.2px

### Components to reuse
- Sticky nav (from index.html)
- Section structure (`section-tag`, `section-title`, `section-sub`)
- Button styles (`.btn`, `.btn-primary`)
- Footer (from index.html — dark green, standard links)
- Card style with subtle border and hover shadows

### Spacing
- Section padding: 88px vertical (desktop), 64px (mobile)
- Content max-width: 780px (narrower than homepage for readability)
- FAQ item spacing: 24px between items

---

## Implementation Notes

### Existing support.html
A basic support page already exists at `/support.html`. It follows much of this spec already. Key improvements to make:

1. **Add troubleshooting section** — covers common technical issues
2. **Add notification/calendar FAQs** — frequent pain points
3. **Update nav** — use the same sticky nav from index.html with logo
4. **Match footer exactly** — use the full homepage footer
5. **Add mobile jump links** — optional enhancement

### Accessibility
- All headings use proper hierarchy (h1 → h2 → h3)
- Links are descriptive ("Email us" not "Click here")
- Colour contrast meets WCAG AA
- Touch targets ≥44px on mobile
- Email link uses `mailto:` for native client opening

### SEO
- Title: "Support — Rally"
- Meta description: "Get help with Rally. Find answers to common questions about circles, tasks, invites, notifications, and more."
- Structured data: Consider FAQ schema for rich results

---

## Success Metrics (Future)

Once analytics are in place, track:
- **Page views** — are users finding support?
- **Contact clicks** — what % still need to email?
- **Time on page** — are users reading or bouncing?
- **Search queries** (if search added) — what are users looking for?

Goal: High page views + low contact rate = self-service is working.

---

## Summary

The Support page should feel like a helpful extension of Rally's care-first brand. Users arrive frustrated or confused — meet them with warmth, clear answers, and an easy path to human help if needed.

**Key principles:**
1. Answer the question first, explain second
2. Keep it scannable — most users won't read everything
3. Make contact easy but encourage self-service
4. Match the homepage warmth — no corporate tone
5. Mobile-first — most Rally users are on phones

---

*Last updated: 2026-03-14*
