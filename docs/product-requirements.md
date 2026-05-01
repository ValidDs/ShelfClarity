# ShelfClarity Product Requirements and Strategy Document

Status: Draft for founder review  
Owner: Chris  
Prepared by: Professor  
Date: 2026-05-01

## 1. Executive Summary

ShelfClarity is a beauty shelf audit and routine planning product. The core job is to help users understand what beauty products they already own, what each product is likely doing, what may be redundant, what may require caution, what may be missing, and what they should consider buying next.

The winning wedge is not a broad AI beauty, skin, hair, makeup, supplement, wellness, and confidence dashboard on day one. That is too broad, too risky, and too hard to trust. The winning wedge is narrower and sharper:

**Upload your beauty shelf. Get a clear keep, pause, replace, and next-buy plan.**

The product should behave as an educational organization and decision-support tool, not a medical advisor. It should never claim to diagnose, treat, cure, guarantee improvement, identify the definitive cause of a skin issue, or replace a dermatologist, stylist, esthetician, trichologist, or clinician.

The best first commercial product is a paid beauty shelf audit, not a free app with vague AI chat. Users already spend meaningful money on beauty. A credible audit can justify a higher one-time price because it helps users make sense of products they may already have spent hundreds of dollars on.

Recommended initial positioning:

**Your beauty shelf, audited.**

Recommended safer subheadline:

**Understand what to keep, pause, replace, and buy next, based on your products, goals, budget, and routine. Educational guidance only, not medical advice.**

## 2. Brand Name Availability Check

Important: this is a preliminary internet and DNS check, not legal clearance. Before locking a name, Chris should run a proper trademark search through USPTO, state business registries, domain registrars, app stores, and ideally a trademark attorney if the project moves forward.

### Names checked

#### GlowLogic

Preliminary signal: not clean. Search surfaced existing web/company references, skincare/beauty-adjacent usage, and GitHub usage. It remains a good-sounding name, but it should not be locked without deeper legal review.

#### ShelfLogic

Preliminary signal: not clean. `shelflogic.com` is active and appears to be an existing planogram/retail software business. The phrase also has retail shelf-planning meaning, which could confuse the beauty positioning.

#### Shelfie

Preliminary signal: crowded and likely expensive. `shelfie.ai`, `shelfie.app`, and `shelfie.co` showed taken/configured signals, `shelfie.app` appeared listed as a premium domain, and GitHub usage is very heavy. Avoid as the main brand.

#### RoutineIQ

Preliminary signal: not clean enough. `routineiq.com` and `routineiq.app` resolve, although obvious beauty/skincare usage did not appear in the quick check. Still not ideal as the working brand if we want availability headroom.

#### ShelfClarity

Preliminary signal: strongest checked option so far. `shelfclarity.com`, `shelfclarity.ai`, `shelfclarity.app`, and `shelfclarity.co` showed no DNS resolution in the quick check, and GitHub search showed no obvious repository conflicts. This does not guarantee availability, but it is the cleanest first-pass option.

### Current naming recommendation

Use **ShelfClarity** as the working brand for now.

Use **Shelf Audit** as the first product/wedge.

Example:

**ShelfClarity**  
**Your beauty shelf, audited.**

This name is less glamorous than GlowLogic, but it is clearer, more trust-oriented, more aligned to the wedge, and appears cleaner in preliminary availability checks.

### Naming caveat to preserve

The current ShelfClarity availability review is **not legal clearance**. It was only a practical first-pass check using DNS, web search, GitHub, and page fetches. Before truly locking the name, purchasing domains, filing marks, or building public brand equity around it, Chris should run a proper trademark/domain/app-store review and ideally consult a trademark attorney.

## 3. Product Thesis

Beauty shoppers have more products and advice than clarity.

They are influenced by TikTok, Sephora, Ulta, Amazon reviews, friends, dermatologists, estheticians, hair stylists, influencers, brand marketing, and ingredient trends. The result is an expensive, emotionally loaded pile of products with no clear operating system.

The user is not asking for a medical diagnosis. The user is asking:

- What do I own?
- What does each product do?
- What should I actually use?
- What should I stop using for now?
- What is redundant?
- What might not belong together?
- What am I missing?
- What should I buy next if I only buy one thing?
- How do I turn this shelf into a routine I can follow?

The product wins if it turns confusion into a practical routine plan while being careful, transparent, and humble about its limits.

## 4. Problem Statement

The modern beauty user is overloaded.

They buy products based on trends, influencer recommendations, sales, impulse, product claims, and emotional moments. Over time they accumulate cleansers, serums, actives, moisturizers, SPF, oils, masks, shampoos, conditioners, leave-ins, styling products, supplements, and tools. They often do not know what each product does, whether products overlap, whether their routine is too complicated, or whether they are buying new products while ignoring essentials.

The current alternatives are flawed:

- TikTok gives inspiration but also contradictory advice.
- Ingredient websites educate but do not personalize or build a routine.
- Dermatologists are credible but may be expensive, unavailable, or used only after serious issues.
- Sephora and Ulta recommend products, but they are retail-first and sell more items.
- Friends and creators are relatable but not systematic.
- Generic AI chat can be confident, unsafe, or ungrounded.

The gap is a trusted, practical, user-controlled audit of what the person already owns.

## 5. Target Customer

### Primary early customer

Beauty overbuyers, mostly women 18 to 35, who buy from TikTok, Sephora, Ulta, Amazon, Target, and influencer recommendations.

They have:

- 10 to 40 beauty products at home.
- Products they forgot they owned.
- Half-used bottles.
- Concern about wasting money.
- Interest in improving skin, hair, or general appearance.
- Anxiety that they may be using too much or mixing the wrong things.
- Willingness to spend if the output feels credible and specific.

### Secondary customers

- Beauty beginners who want a simple routine.
- Busy professionals who want fewer decisions.
- Event-prep users preparing for weddings, vacations, photoshoots, birthdays, interviews, or dates.
- Budget-conscious beauty buyers trying to stop impulse spending.
- Skincare/haircare enthusiasts who want better organization.

### Poor early customers

- Users with severe or diagnosed medical conditions who need clinical care.
- Users expecting guaranteed transformation.
- Users with only 2 or 3 basic products, unless positioned as beginner routine setup.
- Users who do not spend on beauty and have no intent to change.

## 6. Jobs To Be Done

Functional jobs:

1. Organize my beauty products.
2. Understand what each product does.
3. Build a routine from what I already own.
4. Avoid obvious redundancy.
5. Identify potential caution areas.
6. Decide what to buy next.
7. Avoid spending money on products I do not need.
8. Prepare for an event with a simple plan.

Emotional jobs:

1. Feel less confused.
2. Feel more in control.
3. Feel like my products have a purpose.
4. Feel confident that I am not wasting money.
5. Feel reassured that my routine is not chaotic.
6. Feel guided without being judged.

Social jobs:

1. Feel more confident in appearance-related decisions.
2. Share a beauty shelf audit result with friends.
3. Compare routines with peers.
4. Feel smarter than impulse-buying from every trend.

## 7. Product Scope

### MVP scope

The MVP is a paid audit report.

Required features:

1. Landing page with clear promise and safety positioning.
2. Intake quiz.
3. Product shelf photo upload.
4. Product extraction from photo.
5. Manual product correction flow.
6. Product categorization.
7. Audit labels.
8. AM/PM routine plan.
9. Potential conflict notes.
10. Missing essentials section.
11. Next best purchase recommendation.
12. Downloadable or shareable report.
13. Payment flow.
14. Human-readable disclaimers.

### Post-MVP scope

1. Monthly routine refresh.
2. Progress check-ins.
3. Product comparison before buying.
4. Refill reminders.
5. Event prep plans.
6. Haircare expansion.
7. Budget tracker.
8. Affiliate purchase links.
9. Dermatologist/esthetician review option.
10. Mobile app.

### Explicitly out of scope for MVP

1. Medical diagnosis.
2. Treatment claims.
3. Severe acne management.
4. Hair loss diagnosis.
5. Supplement recommendations beyond caution flags.
6. Prescription management.
7. Community/social feed.
8. Full marketplace.
9. Guaranteed progress tracking.
10. Automated claims that a product caused a reaction.

## 8. Core User Flow

### Step 1: Landing page

User lands on a page that says:

**Your beauty shelf, audited.**

Subcopy:

**Upload your products and get a practical keep, pause, replace, and next-buy plan built around your goals, budget, and routine. Educational guidance only, not medical advice.**

Primary CTA:

**Start my shelf audit**

Secondary CTA:

**See example report**

### Step 2: Intake quiz

Questions:

1. What do you want help with? Skin, hair, both, general product cleanup.
2. What are your top goals? Simpler routine, fewer breakouts, hydration, texture, dullness, frizz, hair strength, budget cleanup, event prep.
3. What is your skin type, if known? Oily, dry, combo, sensitive, not sure.
4. What is your hair type, if included? Straight, wavy, curly, coily, not sure.
5. Any known sensitivities or allergies?
6. Any prescription products?
7. Any diagnosed skin or scalp conditions?
8. Are you pregnant, breastfeeding, or trying to conceive? Optional but important for caution routing.
9. How many steps are you willing to do? Minimal, balanced, advanced.
10. Monthly beauty budget.
11. Preferred stores, optional.

Safety handling:

If user indicates diagnosed condition, prescription use, pregnancy, severe irritation, hair loss, or active rash, show:

**ShelfClarity can help organize your products and routine, but it cannot diagnose or treat medical conditions. For these concerns, use this audit as a discussion aid with a licensed professional.**

### Step 3: Shelf upload

User uploads:

- Shelf photo.
- Individual product photos if needed.
- Ingredient labels if visible.

The app extracts likely product names and categories.

### Step 4: Product confirmation

User sees extracted products and confirms:

- Product name.
- Brand.
- Category.
- Frequency of use.
- Whether they like it.
- Whether it causes any known reaction.
- Whether they intend to repurchase.

This step is critical. It reduces AI errors and improves trust.

### Step 5: Audit generation

The system produces product-level labels:

- Keep.
- Pause for now.
- Use carefully.
- Likely redundant.
- Low-priority repurchase.
- Missing essential.
- Ask a professional.
- Unknown, needs better label photo.

### Step 6: Routine output

The user receives:

1. AM routine.
2. PM routine.
3. Weekly rhythm.
4. Recovery days.
5. Product priority order.
6. One next purchase category.
7. Optional shopping guidance.
8. Caution notes.
9. Confidence labels.

### Step 7: Payment and report delivery

Two possible approaches:

Option A: Pay before upload. Cleaner but higher friction.
Option B: Free extraction preview, then pay for full audit. Better for conversion.

Recommended: Option B.

Free preview:

- “We found 17 products.”
- “Looks like you have 4 treatment products, 3 moisturizers, and no confirmed daily SPF.”
- “Unlock your full keep, pause, replace, and routine plan.”

## 9. Recommendation System Design

Do not build this as pure freeform AI.

The safer architecture:

1. Product extraction layer.
2. Product database and fallback web lookup.
3. Ingredient/category parser.
4. Rules engine.
5. Confidence scoring.
6. AI explanation layer.
7. Safety language layer.
8. User confirmation loop.

### Recommendation categories

Keep:

Product appears aligned with stated goals and has a clear place in routine.

Pause for now:

Product may be duplicative, aggressive, hard to evaluate, or not needed while simplifying.

Use carefully:

Product may involve common irritation risks, active ingredients, strong fragrance, exfoliants, retinoids, or combining concerns.

Likely redundant:

Multiple products serve similar role.

Missing essential:

A foundational category appears absent, such as SPF for daytime routines.

Ask a professional:

The user disclosed a condition or product category that requires care.

Unknown:

The app does not have enough product or ingredient information.

### Confidence labels

Every recommendation should show confidence:

- High: Product and category identified clearly.
- Medium: Product identified, ingredients partially known.
- Low: Product unclear or label not visible.

Example:

**Confidence: Medium. Product name was visible, but full ingredient label was not.**

## 10. Safety and Legal Positioning

The product should be built with conservative language from day one.

### Required disclaimer language

Short version:

**ShelfClarity provides educational beauty routine organization. It does not diagnose, treat, cure, prevent, or replace advice from a licensed professional.**

Long version:

**ShelfClarity is designed to help users organize products, understand common ingredient categories, and build practical routines based on self-reported goals and uploaded products. It is not medical advice. It does not diagnose or treat acne, eczema, rosacea, hair loss, allergic reactions, infections, or any medical condition. If you have persistent symptoms, severe irritation, a diagnosed condition, pregnancy-related concerns, prescription products, or uncertainty about product safety, consult a licensed professional.**

### Banned language

Do not say:

- This will clear your skin.
- This caused your breakout.
- This is safe for you.
- This product is harmful.
- This treats acne.
- Guaranteed results.
- Dermatologist-level advice.
- Medical-grade routine.
- Diagnose your skin.

### Safer alternatives

Use:

- May.
- Might.
- Could.
- Consider.
- Potential.
- Commonly.
- Often.
- Based on the products you shared.
- Based on visible label information.
- Educational guidance.
- Routine organization.
- Confidence: low, medium, high.

## 11. Trust Features

Trust is the product. Without trust, this fails.

Required trust mechanisms:

1. User confirmation before audit.
2. Confidence labels.
3. Ingredient source references.
4. Conservative language.
5. Explanation cards.
6. Clear “why we flagged this” sections.
7. Ability to mark a recommendation as wrong.
8. Ability to export report for a dermatologist or stylist.
9. Clear professional-care escalation prompts.
10. No hidden brand sponsorship in recommendations.

Future trust enhancer:

Paid human review from a licensed esthetician, dermatologist, or hair professional. This can be positioned as an optional premium add-on.

## 12. Pricing Strategy

Pricing can and should be higher than a generic app because this is a specific, high-value audit around products the user already bought.

### Recommended pricing ladder

Free preview:

- Product extraction up to 8 products.
- Category summary.
- No full keep/pause routine.

Starter audit: **$29**

- Up to 12 products.
- Skin-only or hair-only.
- Keep/pause/replace labels.
- Simple AM/PM routine.
- One next purchase category.

Full shelf audit: **$49**

- Up to 25 products.
- Full keep/pause/replace report.
- Potential conflict notes.
- Missing essentials.
- AM/PM routine.
- Weekly rhythm.
- Budget cleanup.
- One next purchase recommendation.

Premium audit: **$89**

- Up to 50 products.
- Skin and hair.
- Event prep plan.
- Product budget review.
- 30-day routine plan.
- One follow-up refresh.

Subscription later: **$14.99 to $19.99/month**

Only after audit demand is proven. Includes monthly refresh, progress check-ins, refill reminders, product comparison before purchase, and routine updates.

My pricing recommendation for beta:

- Free preview.
- $49 full audit.
- $89 premium audit.

Do not start too low. Low pricing can reduce perceived trust and attract low-intent users.

## 13. MVP Requirements

### User requirements

As a user, I want to upload my products so I can understand what I own.
As a user, I want to confirm extracted products so the audit is accurate.
As a user, I want a keep/pause/replace plan so I know what to do next.
As a user, I want explanations so I understand why a product was flagged.
As a user, I want confidence labels so I know when the app is unsure.
As a user, I want a simple routine so I can follow it without thinking.
As a user, I want budget guidance so I stop buying duplicates.
As a user, I want safe language so I do not mistake the app for medical care.

### Functional requirements

1. Landing page.
2. Intake questionnaire.
3. Image upload.
4. Product extraction.
5. User confirmation table.
6. Product classification.
7. Rules-based audit engine.
8. AI-written explanations with safety filters.
9. Audit report UI.
10. Payment integration.
11. Report email or download.
12. Basic admin view for audits.

### Non-functional requirements

1. Privacy-conscious handling of images.
2. Clear data deletion option.
3. Fast upload and processing.
4. Mobile-first design.
5. Error recovery if product recognition fails.
6. Audit output should be readable by non-technical users.
7. Recommendations should be traceable to product category, ingredient category, or user goal.

## 14. Data and Privacy

Beauty shelf photos may reveal private lifestyle information. The product must treat uploads as sensitive.

Requirements:

- Explain what photos are used for.
- Do not use photos for training without explicit consent.
- Allow deletion.
- Store minimal data.
- Blur or ignore unrelated personal background where possible.
- Avoid collecting medical history beyond what is needed for caution routing.
- Encrypt stored images if retained.
- Consider auto-deleting raw images after audit completion.

## 15. Metrics

### Pre-launch metrics

- Landing page conversion to start audit.
- Quiz completion rate.
- Upload completion rate.
- Free preview to paid conversion.
- Average products uploaded.
- Willingness to pay by price point.

### MVP success metrics

- Paid audit conversion: target 3 to 8 percent from landing visitors.
- Free preview to paid conversion: target 10 to 25 percent.
- Audit satisfaction: target 70 percent say “useful” or better.
- Report completion: target 80 percent view full report.
- Referral intent: target 30 percent would share with a friend.
- Refund rate: below 8 percent.

### Long-term metrics

- Repeat refresh purchase rate.
- Subscription conversion after audit.
- Monthly active users.
- Product comparison usage.
- Affiliate conversion.
- Net promoter score.
- Trust score.

## 16. Go-To-Market Strategy

### Best wedge campaign

**Show us your shelf. We’ll tell you what to keep, pause, replace, and buy next.**

This is visual, clear, and TikTok-friendly.

### Channels

1. TikTok organic.
2. Beauty Reddit communities, carefully and non-spammy.
3. Instagram Reels.
4. Micro-influencer audits.
5. Sephora/Ulta haul cleanup content.
6. “I spent $400 on skincare and do not know what to use” content.
7. Before/after shelf organization content, not skin-result claims.

### Content ideas

- “Your shelf is not a routine.”
- “Three signs your skincare routine is fighting itself.”
- “What I would pause if this were my shelf.”
- “You probably do not need five serums.”
- “One product category most routines are missing.”
- “Stop buying before you audit.”

## 17. Competitive Landscape

Competitors and substitutes:

- INCI Decoder.
- Think Dirty.
- Yuka.
- Skin Bliss.
- TroveSkin.
- Sephora recommendations.
- Ulta recommendations.
- TikTok creators.
- Dermatologists and estheticians.
- Generic AI chat.

Differentiation:

ShelfClarity should not compete as the biggest ingredient database. It should compete as the most practical routine organizer.

Positioning:

- Ingredient apps explain products.
- Retailers sell products.
- Creators recommend products.
- ShelfClarity audits what you already own and helps decide what to do next.

## 18. Major Risks

### Risk 1: Legal/health claims

Mitigation:

- Conservative language.
- No diagnosis.
- No guarantees.
- Safety escalation.
- Confidence labels.
- Clear disclaimers.

### Risk 2: Bad recommendations

Mitigation:

- Rules engine.
- User confirmation.
- Unknown states.
- Human review option.
- Feedback loop.

### Risk 3: Product recognition failure

Mitigation:

- Manual correction.
- Barcode scan later.
- Product search fallback.
- Ingredient label upload.

### Risk 4: Too broad

Mitigation:

- Start with shelf audit.
- Avoid full wellness dashboard.
- Focus on skin first, hair optional as premium.

### Risk 5: Lack of trust

Mitigation:

- Show reasoning.
- Cite common guidance.
- Use confidence levels.
- Avoid sponsorship bias.
- Add professional review later.

## 19. Build Phases

### Phase 0: Validation

- Landing page.
- Example report.
- Waitlist or paid beta.
- Manual concierge audits behind the scenes.

### Phase 1: Concierge MVP

- User uploads shelf.
- Semi-manual extraction.
- AI/rules-assisted report.
- Human QA before delivery.
- Charge $49 to $89.

### Phase 2: Automated MVP

- Automated extraction.
- User confirmation.
- Rules-based recommendations.
- Payment and report generation.

### Phase 3: Retention layer

- Monthly refresh.
- Progress check-ins.
- Product comparison before purchase.
- Refill reminders.

### Phase 4: Expansion

- Haircare.
- Event prep.
- Professional review marketplace.
- Affiliate marketplace.

## 20. Brutal Verdict

ShelfClarity has real business potential because the pain is emotional, recurring, and tied to existing spending. The market is crowded, but the shelf audit wedge is sharp enough to cut through if executed carefully.

The product must not pretend to be a dermatologist. It must be a trusted routine organizer and product decision-support tool. The safest and strongest version is specific, practical, and humble.

Build this if the first landing page and concierge audits show users will pay $49 or more for clarity.

Do not build the full app before proving that people will pay for the audit.
