# PR-FAQ Final Assignment: Tesla Model Y FSD: Earn Mode

**MGMT 275: Assignment #5**  
Kevin Meng, Ethan He | May 2026

---

## Section 1: Submission Items

**One-liner:** For cost-conscious Tesla Model Y owners who see FSD's $99/month price as a luxury they cannot justify, Earn Mode turns their idle vehicle into an income-generating robotaxi, making FSD a self-funding investment instead of a recurring expense.

**Primary User:** Cost-conscious mainstream HW4 Model Y owners (the ~88% of Tesla's 8.9M-vehicle fleet that does not currently subscribe to FSD), particularly those in pilot Robotaxi metros (Austin, Phoenix, Dallas).

**Key Features to Test in the Prototype:**

- **Dashboard tab:** Earn Mode on/off toggle with live vehicle status pill, monthly FSD offset progress bar (earnings vs. subscription cost), and a quick-stats grid showing trips completed, average trip rating, total Robotaxi miles, and disengagement count
- **Schedule tab:** day-of-week availability chips (Mon–Fri default), time-window controls (9 AM–6 PM default), minimum battery reserve (20% default), auto-return home toggle with geo-fenced home zone, and a live weekly bar chart that recalculates projected earnings as owners adjust days and hours
- **Earnings tab:** month-to-date total with week-by-week bar chart, available-payout card with one-tap bank transfer, and an interactive real-world map (OpenStreetMap/Leaflet, dark-themed) plotting completed Robotaxi routes as color-coded lines with clickable pickup/drop-off markers showing route and fare
- **Settings tab:** trip radius cap (25 mi default), battery reserve floor, per-trip notification toggle, auto-cleaning cadence selector, bank account management, and live Tesla $2M commercial Robotaxi insurance status indicator
- **Live trip overlay (Dashboard):** when Earn Mode is active and a trip is in progress, an animated card appears showing route, distance, accumulating fare counter, and estimated minutes remaining — disappearing automatically when the trip ends

---

## Narrative / Press Release

### Tesla Launches Earn Mode: Turning Model Y Owners Into Autonomous Income Earners

**Austin, TX | September 15, 2026**

"My Model Y just sits in the office parking lot for nine hours a day," says Marcus Chen, a 34-year-old software engineer in Austin. "Last week it made $312 while I was at work. That is more than my car payment." Chen is one of 1,200 owners who joined Tesla's closed Earn Mode beta in August 2026. He is also among the first wave of what Tesla expects will become hundreds of thousands of consumers earning passive income from their FSD-equipped vehicles in the next eighteen months.

Today, Tesla is opening Earn Mode to all HW4 Model Y owners with an active FSD subscription in three pilot metros: Austin, Phoenix, and Dallas. Owners can enroll their parked vehicle into Tesla's managed Robotaxi network during idle hours, set their own availability windows, and receive weekly payouts for the miles their car drives. Tesla remains the operator, the insured party, and the customer-facing brand. Owners receive 70 percent of net trip revenue after Supercharger, insurance, and cleaning costs are deducted.

The thesis behind Earn Mode is simple. The average car in America sits unused for 95 percent of its life. Tesla now has more than 4 million Model Ys on the road and over 8 billion cumulative FSD miles trained into its neural network. By unlocking even a fraction of that idle capacity, Tesla is converting a depreciating consumer asset into the world's first mass-market income-generating autonomous platform. Analyst projections from Wolfe Research and ARK Invest place per-vehicle earnings between $400 and $1,200 per month at moderate utilization in pilot cities, with high-demand metros and overnight availability pushing the upper bound higher.

> "For the past decade, owners paid Tesla. With Earn Mode, Tesla pays owners. We are turning every Model Y into the first mass-market income-generating consumer asset in history. This is the vision Elon laid out in Master Plan Part Deux back in 2016, and the technology has finally caught up to the ambition."
> — Tesla VP of Autonomy Products

Here is how it works. An eligible owner opens the Tesla app and taps Earn Mode in the main menu. The Dashboard tab shows a personalized monthly earnings estimate and an FSD offset progress bar tracking how much of the subscription cost the car has already earned back. The owner opens the Schedule tab, selects available days using day-of-week chips, sets a time window (defaulting to weekdays 9 AM–6 PM), configures a minimum battery reserve floor (20 percent by default), and enables auto-return home within their geo-fenced home zone. A live bar chart updates projected weekly earnings in real time as the owner adjusts days and hours. They confirm. Tesla handles the rest: dispatching trips, vetting riders, routing to Superchargers between trips, processing payments, providing commercial insurance, and crediting owners for any cleaning or wear costs.

Crucially, owners stay in control. The Tesla app lets owners pause Earn Mode instantly, set a 90-minute guaranteed return-to-home window, blacklist destinations or neighborhoods they prefer to avoid, and cap the trip radius to 25 miles by default, and review every trip on a transparent Earnings tab featuring an interactive real-world map of completed routes, a per-trip fare breakdown, and a one-tap payout transfer to a linked bank account. Every trip is recorded by interior cameras (audio off by default), and a $250 trip-by-trip damage guarantee covers any rider-caused wear.

> "Earn Mode is the missing piece that makes FSD economically self-justifying. Owners have told us for two years that $99 a month felt steep for a system they still had to supervise. Now the math is different. If your car earns $400 a month and FSD costs $99, you are net positive $300. The subscription stops being an expense and becomes an investment in an asset that pays you back."
> — Tesla Product Lead

Earn Mode is available today in Austin, Phoenix, and Dallas. Tesla plans to expand to Houston, Miami, Orlando, Tampa, and Las Vegas by the end of 2026, contingent on local regulatory approval for unsupervised FSD operation. Interested owners can join the waitlist immediately through the Tesla app. To learn more, visit [tesla.com/earn](https://tesla.com/earn).

---

## External FAQs

*Questions a Tesla owner or prospective owner is likely to ask.*

**1. How do I enroll my Model Y in Earn Mode?**

Open the Tesla app, tap Earn Mode in the main menu, and follow the onboarding flow. You must have an HW4-equipped Model Y, an active FSD subscription, and live in a city where Earn Mode is available (currently Austin, Phoenix, and Dallas). Enrollment takes about three minutes. You set your availability windows, confirm a brief interior inspection via the in-car camera, and you are ready to earn. Tesla activates your enrollment within 24 hours after a final vehicle health check.

**2. How much can I expect to earn?**

Earnings depend on your city, your availability hours, and local Robotaxi demand. In our beta, the median owner earned about $480 per month with 30 weekly hours of availability, and the top quartile earned over $900 per month. The Tesla app shows you a personalized monthly estimate based on your zip code before you enroll, and the estimate updates daily as you build a history. We deliberately quote conservative ranges; we would rather underpromise than overpromise.

**3. What if my car is damaged or dirty after a trip?**

Every Earn Mode trip is covered by Tesla's $250 trip-by-trip damage guarantee for minor cleaning and wear. Major damage is covered by Tesla's **$2M commercial Robotaxi insurance policy**, which fully replaces the personal auto policy while your vehicle is on an Earn Mode trip. If your car needs cleaning, Tesla dispatches a partner to clean it before its next trip and credits the cost. You will see all of this on the trip detail screen in the Tesla app.

**4. What if I need my car unexpectedly?**

Tap "Call My Car Home" in the Tesla app. Earn Mode guarantees your vehicle is back at your designated home location within 90 minutes, regardless of whether it is mid-trip. If your car is currently carrying a rider, it will complete that trip and then return; if it is empty, it returns immediately. We track the on-time rate per owner and refund a small inconvenience credit if we ever miss the 90-minute window.

**5. Does Earn Mode cost anything extra beyond my FSD subscription?**

No. There is no enrollment fee, no monthly fee, and no equipment to install. You keep your $99/month FSD subscription as-is. Tesla deducts a platform fee from each trip's revenue (clearly itemized in your trip dashboard), and your 70 percent payout is after Supercharger energy, insurance, and any cleaning costs. Earn Mode is a revenue-share, not a subscription upsell.

**6. What does the rider see? Will they know whose car they are in?**

Riders see a generic Tesla Robotaxi vehicle in the customer app, not the owner's name or photo. From the rider's perspective, every Earn Mode trip feels identical to a Tesla-owned Cybercab trip: they request a ride, the nearest available vehicle is dispatched, and the car arrives autonomously. Owners are anonymized end-to-end. We do not share owner identity, address, or any personal data with riders.

**7. Who is liable if there is an accident while my car is on an Earn Mode trip?**

Tesla is. The moment your vehicle starts an Earn Mode trip, your personal auto policy steps aside and Tesla's commercial Robotaxi policy takes over. Tesla, not the owner, is the named insured and the operator under state TNC regulations. This is the legal architecture that distinguishes Earn Mode from a peer-to-peer ride-share model.

**8. Is Earn Mode available in my city?**

Today, Earn Mode operates in Austin, Phoenix, and Dallas. Tesla is rolling out to Houston, Miami, Orlando, Tampa, and Las Vegas by Q4 2026, pending state-level approval for unsupervised FSD operation. You can join the Earn Mode waitlist for your city in the Tesla app today. We will notify you the moment Earn Mode goes live in your metro and prioritize early waitlist members in the initial enrollment wave.

**9. Can I restrict where my car goes or what kinds of trips it accepts?**

Yes. You can blacklist specific destinations, neighborhoods, or zip codes. You can cap maximum trip distance (the **app defaults to 25 miles** in the Settings tab, which you can raise or lower). You can opt out of overnight hours, airport runs, or event-driven surges. The default settings are designed to maximize earnings, but every restriction is one tap away in the app. Restrictions reduce earnings, and the app shows you the projected earnings impact of each setting in real time.

**10. How does Earn Mode affect my battery life and Supercharger costs?**

Tesla manages all charging during Earn Mode trips. Your vehicle will Supercharge automatically between trips to maintain at least your **configured battery reserve floor (defaulting to 20 percent in the Settings tab, adjustable up to 50 percent)**, stopping new trip dispatch below that threshold. All Supercharger costs are paid by Tesla and deducted before your 70 percent payout. We monitor your battery health via the same telemetry that powers the existing Tesla warranty system, and Earn Mode usage does not affect your battery warranty. If your battery degrades faster than the warranty curve due to Earn Mode usage, Tesla covers the gap.

---

## Internal FAQs

*Questions internal executives, partner teams, engineering, design, legal, and finance are likely to ask.*

**1. Why now? Why not wait for full unsupervised FSD approval everywhere?**

Three reasons. First, we already have unsupervised FSD operating commercially in Austin (10 Model Ys, $4.20 flat fare, no safety driver, since April 2026), so the regulatory pattern is established for at least one metro. Second, Wolfe Research projects our fleet scaling to ~7,200 robotaxis by end of 2026, but our Cybercab production alone cannot meet projected demand in seven expansion metros. Earn Mode lets us scale to suburbs and second-tier neighborhoods faster than Cybercab production allows. Third, Waymo just announced the 50,000-unit Hyundai IONIQ 5 deal targeting 2028. If we wait, Waymo scales a cheaper, purpose-built L4 fleet faster than we scale our consumer-contributed fleet, and our structural capital-efficiency advantage erodes. We need to defend the moat now.

**2. What is our pricing/revenue-split rationale?**

Owners receive 70 percent of net trip revenue after Supercharger energy, insurance, and cleaning costs are deducted. We modeled this against three anchors: Uber/Lyft driver take-rates (~75 percent of gross), Airbnb host take-rates (~85 percent), and Turo car-share take-rates (~70 to 80 percent). We chose 70 percent of net (rather than gross) because we, not the owner, bear all operating costs. This structure gives owners a meaningful but sustainable share while protecting Tesla's unit economics. At our $4.20 base fare and current Austin utilization, a typical owner earns about $480/month net; Tesla retains about $200/month per enrolled vehicle in platform contribution margin.

**3. How do we handle insurance and liability when a personal vehicle is in commercial use?**

Tesla Insurance writes a separate commercial Robotaxi policy that activates the instant a vehicle starts an Earn Mode trip and deactivates when the trip ends. During Earn Mode trips, Tesla is the named insured and the operator of record. The owner's personal auto policy is held harmless. This is the same legal structure Tesla already uses for the Austin pilot fleet. We have written sign-off from Tesla Insurance's actuarial team and outside counsel opinion letters in three pilot states.

**4. What is our SMART success metric and how does it ladder to the North Star?**

- **Specific:** 20 percent of HW4 Model Y owners in pilot metros enrolled in Earn Mode within 12 months of launch
- **Measurable:** tracked weekly via the Earn Mode enrollment dashboard
- **Achievable:** benchmarked against Airbnb host activation, Uber driver onboarding, and residential solar enrollment curves
- **Relevant:** leading indicator for our North Star metric — FSD subscription take-rate (target: 25 percent of the global fleet within 18 months, up from 12.4 percent today)
- **Time-bound:** 12 months from public launch

Secondary metrics: $400 median monthly owner earnings, 99.5 percent on-time return-to-home, less than 0.5 percent trip-level incident rate.

**5. Why launch in Austin, Phoenix, and Dallas first?**

Three criteria: regulatory readiness, infrastructure density, and weather. Austin already hosts our commercial Robotaxi pilot and has the most permissive unsupervised AV regulatory environment in the US. Phoenix has clear weather year-round (critical for vision-only FSD) and a state government that has actively courted AV deployment since 2017. Dallas combines suburban density with a recent state-level TNC clarification that explicitly permits Tesla's operator-of-record structure. We deliberately excluded California because of the active Tesla Insurance enforcement action and CPUC ambiguity around unsupervised consumer-vehicle dispatch.

**6. What is the regulatory risk, especially around TNC classification?**

The largest open question is whether state regulators classify Earn Mode as a TNC operation, which would impose commercial licensing requirements on individual owners. Our defense is that Tesla, not the owner, is the operator, the insured party, and the customer-facing entity; the owner is a passive asset contributor analogous to an Airbnb host. We have aligned with state AV regulators in Texas, Arizona, and Florida. Mitigation: in any state that rules Earn Mode is a TNC operation requiring per-owner licensing, we absorb the licensing cost on behalf of the owner up to $250/year.

**7. How does Earn Mode complement (rather than cannibalize) the Tesla-owned Cybercab fleet?**

Cybercab is concentrated in core urban zones where the per-trip economics are tightest. Earn Mode extends Robotaxi coverage to suburban and second-tier neighborhoods where Cybercab fleet density would be capital-inefficient. The two fleets are complementary on geography (Cybercab dense urban, Earn Mode suburban), time (Cybercab 24/7, Earn Mode owner-window-bounded), and trip type (Cybercab high-utilization shuttles, Earn Mode lower-utilization but capital-light). Our dispatch system already routes the optimal vehicle from a heterogeneous fleet; we are simply adding more nodes to the network.

**8. What is the unit economics model and how do we get to profitability?**

Per active Earn Mode vehicle per month at moderate utilization (35 hrs/week, 60% fill rate):

| Line Item | Amount |
|---|---|
| Gross revenue | ~$870 |
| Supercharger energy | ~$130 |
| Insurance | ~$95 |
| Cleaning | ~$60 |
| **Net revenue** | **~$585** |
| Owner payout (70%) | ~$410 |
| **Tesla platform contribution** | **~$175** |

At 200,000 enrolled vehicles by end of 2027: **$35M monthly contribution margin** from Earn Mode alone. The much larger value is the implied FSD subscription growth: if Earn Mode lifts FSD take-rate from 12.4 percent to 20 percent across the 8.9M-vehicle fleet, that is an incremental ~670,000 FSD subscribers at $99/month, or **~$800M of incremental annual recurring revenue**.

**9. What experiments have we run, what is in flight, and what do we project?**

- **Layer 1 (designed, not yet executed):** 28-day pre-launch A/B test of the Earnings Estimator on the FSD subscription page (Control / T1 estimator card / T2 estimator + waitlist CTA). Projected outcome: T2 delivers a 15–25 percent relative lift in FSD conversion.
- **Layer 2 (in flight on the prototype):** Small directional validation of hero-copy framing on our live prototype, posted to Tesla owner communities. Sample target: 100+ visitors per arm. Results directional only.
- **Layer 3 (proposed for production):** 60-day closed beta in Austin (1,200 owners) with surveys, NPS, on-time SLA tracking, and incident telemetry before broader rollout.

**10. How does Earn Mode affect FSD take-rate, and how confident are we in the lift?**

Base case: **+10 percentage points** to FSD take-rate within 18 months in pilot metros (from 12.4 percent to ~22 percent). Confidence: moderate (~65–70 percent). Evidence: (1) Earnings Estimator A/B test projected 15–25 percent relative conversion lift; (2) "I would subscribe because the car pays for it" is the single most cited reason for net-new subscription interest among non-subscribers; (3) cost-conscious mainstream segment represents 88 percent of the addressable Model Y fleet.

**11. What are the failure modes if owners are dissatisfied?**

| Failure Mode | Likelihood | Mitigation |
|---|---|---|
| Earnings under-delivery | High | Conservative 10th–50th percentile estimator; $100/month guaranteed minimum for first 90 days |
| Cleanliness/damage incident | Medium | $250 trip-by-trip guarantee; interior camera evidence; partner cleaning network |
| Return-to-home SLA miss | Low | SLA-protected dispatch logic; $50 inconvenience credit per miss |
| Battery degradation concern | Medium | Battery-warranty backstop; transparent battery health dashboard |

**12. What is the engineering and tech stack?**

Earn Mode is a thin orchestration layer on top of three existing systems: the Tesla mobile app, the Tesla Robotaxi dispatch system, and Tesla Insurance. New components:

- **Earnings Estimator service:** Python/FastAPI on Tesla AWS; pulls zip-code-level Robotaxi demand, projects per-vehicle monthly earnings as a 10th–50th percentile range
- **Availability Scheduler service:** Go service that gates which enrolled vehicles are dispatchable at any moment; integrates with vehicle telemetry
- **Owner Payout Engine:** Stripe Treasury for weekly ACH disbursements; trip-level itemization, tax-form generation (1099)
- **LLM Dispatch Optimizer:** PyTorch fine-tuned model + deterministic combinatorial solver fallback for multi-constraint edge cases

Stack: Python/Go on Tesla AWS, React Native in the Tesla app, PyTorch for dispatch and earnings ML models.

**13. What growth-hacking levers do we have to drive owner enrollment?**

1. Earnings Estimator card on the FSD subscription page (A/B test in A.5)
2. In-vehicle prompts: "Your car could be earning right now" nudge after 4+ hours idle in a pilot metro
3. Referral program: $200 for referring owner + $200 for new enrollee after first 100 paid miles
4. City-level earnings transparency dashboards on tesla.com (real anonymized data)
5. Co-marketing with suburban employers (office parks where employee Teslas sit idle 9 hrs/day)

**14. What happens if Waymo, Uber, or Lyft respond with their own owner-network model?**

Waymo cannot replicate Earn Mode — they have no consumer vehicle fleet. Uber and Lyft do not control the dispatch software, the vehicle, the insurance, or the regulatory operator-of-record status. Our moat is end-to-end vertical integration: chip (HW4) → training (Dojo) → neural net (FSD v14) → vehicle → dispatch → payments → insurance → customer relationship. A competitor would need to replicate all seven layers. The most realistic competitive response is Waymo expanding its consumer leasing program, which would still leave them at ~50 percent higher per-mile cost (per ARK Invest).

**15. How do we handle vehicle wear, depreciation, and the long-term math for owners?**

At high utilization (50+ hrs/week), Earn Mode accelerates vehicle wear by an estimated 1.4x–1.8x relative to private use, primarily affecting tires, brakes, and interior surfaces. Our financial model accounts for this via: (a) the $250 trip-by-trip damage guarantee; (b) Tesla credits for accelerated tire and brake wear at the standard service interval; (c) the 70/30 net split is calibrated so that even after wear and depreciation, owners net a positive return on their FSD subscription cost. We will publish a quarterly "Earn Mode wear study" to maintain transparency.

**16. What is the v1 vs. v2 roadmap?**

**v1 (today):** HW4 Model Y only · three pilot cities · owner-set availability windows · fixed 70/30 net split · English-only app · ACH weekly payouts · US-only

**Explicitly NOT in v1:** Cybertruck/Model 3 support · peer-to-peer leasing · dynamic per-trip owner approval · tiered earnings · international markets · in-app social features

**v2 candidates (12–18 months):** Model 3 HW4 support · owner-customizable interior presets · real-time route-level opt-in · 10 more US metros · multi-city availability for traveling owners

**17. What are the privacy concerns and how are we addressing them?**

| Vector | Policy |
|---|---|
| Owner identity to riders | Fully anonymized; riders never see owner data |
| Interior camera data | Audio off by default; video retained 24 hrs, accessed only for trip flags; never used for ML training |
| Owner location data | Home address anonymized via geofencing ("within one mile of") when shared with dispatch system |

All three policies are documented in a single Earn Mode privacy notice that owners must affirmatively accept before enrolling. We do not sell, share, or monetize any owner data with third parties.

**18. How do we prevent fraud?**

- **Hardware binding:** Enrollment requires a VIN with an active FSD subscription from a verified payment method, screening out bot enrollment
- **Trip authenticity:** Every trip is initiated by a rider in the Tesla customer app, completed against GPS telemetry, and verified by interior camera; owners cannot self-generate trips
- **Payout reconciliation:** Fraud-detection model flags anomalous patterns; suspicious accounts are held and reviewed manually before payout

---

## Appendix

### A.1 Problem Selection via RICE

| Problem | Reach | Impact | Confidence | Effort | RICE Score |
|---|---|---|---|---|---|
| Low FSD take-rate via Earn Mode income **(selected)** | 7.8M non-subscribers | 3.0 | 0.70 | 8 pm | **2.05M** |
| Cheaper FSD tier ($29/mo light version) | 7.8M non-subscribers | 2.0 | 0.50 | 6 pm | 1.30M |
| Highway-only nag-free FSD mode | 2M commuters | 2.0 | 0.70 | 5 pm | 560K |
| Phantom braking and nag reduction | 1.1M FSD users | 2.0 | 0.80 | 4 pm | 440K |
| Owner trust/cleanliness controls (subset of Earn Mode) | 800K projected enrollees | 1.5 | 0.60 | 3 pm | 240K |

Earn Mode wins on RICE by a **1.6x margin** over the next best alternative. The decisive factor is Impact: Earn Mode is the only candidate that fundamentally reframes the FSD value proposition (from cost to investment) rather than incrementally improving the existing product.

---

### A.2 User Research Methodology

Our user research is a composite synthesis from three sources: (1) qualitative listening across public Tesla owner communities (r/TeslaMotors, r/TeslaLounge, Tesla Motors Club forums) over the eight weeks preceding this assignment; (2) three informal Zoom conversations with Tesla Model Y owners in our personal network conducted between April 29 and May 11, 2026; and (3) segment archetypes identified in our Product Strategy Analysis (Assignment #3).

The ten profiles in A.3 are composite personas representing segments observed repeatedly across all three research sources. The research protocol tested four hypotheses:

1. Owners perceive FSD as expensive for what they get today ✓
2. Earning income from an idle vehicle is intuitively appealing to cost-conscious owners ✓ (8/10 personas)
3. Trust concerns are the dominant adoption barrier ✓ (all 10 personas surfaced at least one)
4. A transparent earnings estimator significantly increases willingness to subscribe ✓ (7/10 personas)

---

### A.3 Composite User Personas

**Persona 1: The Cancelled Subscriber** — Marcus C., 34, Software Engineer, Austin TX
> "I loved FSD during the trial. But $99 a month for something I only use 30 minutes a day? Hard sell. If my car was making money during the day, that's a completely different conversation. I would resubscribe tomorrow."

*Implication:* This is the launch persona. Earn Mode reframes the price entirely.

---

**Persona 2: The Asset-Minded Owner** — Lisa P., 41, Office Manager, Phoenix AZ
> "I am not paying $99 a month so a computer can drive me to Costco. But if you told me my car earned $400 a month while I was at work, I would think about it like Airbnb."

*Implication:* The Airbnb mental model should appear in marketing copy.

---

**Persona 3: The Two-Car Household** — David K., 52, Real Estate Agent, Dallas TX
> "My car is never idle. But I told my wife about it and she immediately said 'can we put my car on this?' Her Model 3 sits in the driveway all day."

*Implication:* v2 should support household-level enrollment.

---

**Persona 4: The Tech-Forward True Believer** — Priya R., 29, Marketing Coordinator, Austin TX
> "The only thing I care about is the earnings being real and the app showing me transparent data. If it looks like Tesla is hiding the math, I will not enroll."

*Implication:* The per-trip revenue breakdown screen is a trust feature, not a nice-to-have.

---

**Persona 5: The Trust Skeptic** — James M., 47, Construction Foreman, Houston TX
> "I do not want strangers in my truck. The earning thing sounds cool but I would have to see the inside of someone's actual car after a year on this thing before I trusted it. Show me the wear."

*Implication:* Market the $250 damage guarantee, interior cameras, and publish a real wear report on beta vehicles after 6 months.

---

**Persona 6: The Shift Worker** — Sarah T., 36, Nurse, Phoenix AZ
> "My car sits in a hospital parking lot for half the day. The only thing I would worry about is needing to leave work early for an emergency and not being able to get home."

*Implication:* The 90-minute return-to-home SLA must be the headline trust feature in onboarding.

---

**Persona 7: The Emotional Owner** — Robert N., 58, Retired Teacher, Las Vegas NV
> "My car is my car. I have a name for her. The thought of some stranger eating fast food in my back seat at 2am while I sleep is unsettling. The money would not be enough."

*Implication:* Genuine non-target. Some owners have an emotional relationship that no financial incentive overcomes. Acceptable — we are not designing for everyone.

---

**Persona 8: The Frequent Traveler** — Maria G., 33, Small Business Owner, Miami FL
> "When I am traveling, my car sits at the Miami airport long-term lot for a week at a time. I pay $25 a day for parking AND the car earns nothing. If Tesla could pick it up from long-term parking and run it as a robotaxi while I am in New York, that would be a game changer."

*Implication:* Airport long-term parking integration is a compelling v2 use case.

---

**Persona 9: The Value-Conscious Convert** — Kevin O., 28, Grad Student, Dallas TX
> "Run the numbers with me. If I pay $99/month for FSD and the car nets me $400/month from Earn Mode, that is $300/month in pure profit. I am subscribing the day this goes live in Dallas, just for the math."

*Implication:* Pure financial framing converts immediately. Highest-velocity conversion target.

---

**Persona 10: The Control-Seeker** — Jennifer A., 44, HR Director, Orlando FL
> "I would do it but only if I could control where it goes. I do not want my car driving through certain neighborhoods at 2am. Make me feel like I am still in charge of my car."

*Implication:* Destination blacklist and time-window controls must be surfaced in the first three onboarding screens, not buried in settings.

---

### A.4 Cross-Cutting Research Insights

| Insight | Implication |
|---|---|
| Mental model is **Airbnb, not Uber** | Lean into the Airbnb "passive asset" framing in all marketing |
| **Earnings transparency is non-negotiable** | Per-trip revenue breakdown screen is a trust feature, not a nice-to-have |
| **Control is the trust unlock** | Destination blacklists, time windows, and 90-min return-to-home SLA must appear in first 3 onboarding screens |
| **Households, not individuals, are the unit of adoption** | 3 of 10 personas surfaced a partner's idle vehicle as the stronger candidate; v2 should support household enrollment |
| **~1 in 10 owners will never enroll** | Emotional vehicle attachment cannot be overcome by financial incentive; acceptable, not designing for everyone |

---

### A.5 Proposed A/B Experiment Design and Projected Outcomes

28-day A/B test of the Earn Mode Earnings Estimator card on the FSD subscription page. Three arms: Control (status quo) / T1 (estimator card) / T2 (estimator + waitlist CTA). Sample: 50,000 unique HW4 Model Y account-holder visitors per arm.

| Metric | Baseline (Control) | T1 Projected | T2 Projected | Launch Criterion |
|---|---|---|---|---|
| FSD subscription conversion rate *(primary)* | ~2.0% | +8 to +12% relative | +15 to +25% relative | T2 ≥ +15% relative lift |
| Waitlist enrollment rate *(T2 only)* | n/a | n/a | 8–14% of visitors | ≥ 8% of visitors |
| 30-day FSD retention *(guardrail)* | 84.1% | Within 3pp of control | Within 3pp of control | No more than 3pp decline |
| Avg time on subscription page *(secondary)* | ~47 sec | +40 to +60% | +70 to +100% | Directional only |
| Earn Mode support tickets / visitor *(guardrail)* | 0.0% | < 0.3% | < 0.5% | < 0.5% of visitors |

**Projection rationale:** Calibrated against three published analogs: (1) residential solar earnings calculators (Sunrun/SunPower: 18–23% conversion lift); (2) Airbnb host-onboarding flows with personalized earnings estimates (15–20% lift in completed listings); (3) Tesla's own solar quote flow.

**Small Directional Validation on the Prototype (May 13–25, 2026)**

Two hero copy variants served randomly via session cookie:
- Variant A: *"Your Model Y can earn money while you don't."*
- Variant B: *"Let your Tesla pay for itself."*

Primary metric: click-through rate from hero CTA to the earnings calculator. Sample target: 100+ visitors per arm (directional only). Decision rule: if Variant B outperforms by more than 20 percent relative on click-through, update the prototype copy.

---

### A.6 Proposed LLM Dispatch Optimizer Evaluation Plan

Eval set: 500 prompts across four categories: standard dispatch (250), multi-constraint edge cases (100), demand prediction (100), adversarial/safety (50).

| Metric | Pre-Launch Target | Justification |
|---|---|---|
| Standard dispatch exact-match accuracy | ≥ 95% | Industry benchmark (IEEE LiMeda 2024) |
| Edge case full/partial credit | ≥ 90% | Multi-reviewer consensus rubric, Fleiss' κ ≥ 0.7 |
| Hallucination rate (full eval set) | < 2% | Safety-critical threshold for AV systems; P0 if violated |
| P95 latency | < 2,000 ms | Rider-perceived responsiveness ceiling vs. Uber/Lyft norm |
| Cost per inference | < $0.005 | Keeps inference cost under 0.25% of $4.20 trip revenue |
| Adversarial refusal rate | 100% | Zero tolerance; any failure blocks deployment |

Deterministic combinatorial solver remains as the production fallback layer. Eval set refreshed quarterly with new real-world dispatch logs to catch model drift.

---

### A.7 Tech Stack and Integration

| Component | Technology | Status |
|---|---|---|
| Client (Tesla mobile app) | React Native | Existing — new Earn Mode tab + onboarding flow added |
| Earnings Estimator service | Python/FastAPI on Tesla AWS | **New** — reads zip-code Robotaxi demand, projects 10th–50th percentile earnings |
| Availability Scheduler service | Go | **New** — gates dispatchable vehicles based on owner windows + vehicle telemetry |
| Dispatch Optimizer | PyTorch fine-tuned model + deterministic solver fallback | Extended — LLM reasoning layer added for multi-constraint edge cases |
| Owner Payout Engine | Stripe Treasury | **New** — weekly ACH, trip-level itemization, 1099 generation |
| Tesla Insurance integration | Commercial Robotaxi policy API | Extended — per-VIN policy issuance, activates/deactivates per trip |

---

### A.8 Known Limitations and v1 Scope Boundaries

| Excluded Feature | Reason |
|---|---|
| Model 3 / Cybertruck support | Different HW3 sensor coverage; safety validation adds 4+ months. v2 candidate. |
| Peer-to-peer (owner-to-individual) leasing | Personal auto insurance excludes commercial ride-hail; liability framework unresolved. Tesla-as-operator structure sidesteps both. |
| Per-trip owner approval | Added dispatch latency degrades rider experience and reduces earnings. Time-window and route rules instead. |
| Premium interior tier | Avoids two-class system fragmenting rider experience in v1. v2 candidate once demand is validated. |
| California / International | California: active Tesla Insurance enforcement action. International: no per-country regulatory framework for unsupervised AVs. |
| Social/community features | Owner-to-owner messaging, leaderboards, referral feeds add complexity without validated demand. Defer to v2. |
| Real-time dynamic pricing for owners | Fixed 70% net split in v1. Simplicity > optimization. v2 may introduce premium availability windows. |

---

### A.9 SMART Metrics

| Type | Metric | v1 Target (12 months) |
|---|---|---|
| North Star | FSD subscription take-rate across global fleet | 20% (up from 12.4%) |
| Primary | % of HW4 Model Y owners in pilot metros enrolled in Earn Mode | 20% |
| Primary | Median monthly owner earnings (across enrolled vehicles) | $400 |
| Growth | FSD subscription conversion lift on Earnings Estimator page | +15% vs. control |
| Engagement | Average active Earn Mode hours per enrolled vehicle per week | 30+ hours |
| Quality | Return-to-home 90-minute SLA on-time rate | 99.5% |
| Safety | Trip-level incident rate (any rider-reported issue) | < 0.5% |
| Guardrail | 30-day FSD subscription retention | ≥ 81% (matches baseline) |
| Guardrail | Owner net promoter score (NPS) for Earn Mode | ≥ 50 |
| Financial | Tesla platform contribution per enrolled vehicle per month | $175 |

---

### A.10 Top Risks (Summary)

| Risk | Mitigation |
|---|---|
| Regulatory delay or TNC reclassification | Tesla absorbs licensing costs up to $250/owner/year |
| Safety incident in pilot metro | Layered safety guardrails: input validation, output constraint enforcement, deterministic dispatch fallback, full audit logging |
| Earnings under-delivery | Conservative range-based estimator (not point estimate); $100/month guaranteed minimum for first 90 days; transparent per-trip breakdown |
| Waymo-Hyundai cost compression | Earn Mode is precisely the response — extends installed-base advantage into the robotaxi competitive surface |
| Vehicle wear and battery degradation | $250 trip-by-trip damage guarantee; battery warranty backstop; quarterly published wear study |

---

### A.11 Sources

1. Electrek: Tesla Q4 2025 earnings disclose 1.1M FSD users (~12.4% of 8.9M fleet). https://electrek.co/2026/01/28/tesla-discloses-fsd-subscriber-count-first-time-1-million/
2. Tesla.com: FSD $99/month subscription-only since Feb 2026. https://www.tesla.com/support/full-self-driving-subscriptions
3. Basenor: Tesla FSD surpasses 8B cumulative miles, Feb 2026. https://www.basenor.com/blogs/news/tesla-fsd-push-8b-miles-99-month-what-owners-should-know
4. Basenor: Tesla Austin Robotaxi fleet reaches 10 unsupervised Model Ys, April 2026. https://www.basenor.com/blogs/news/tesla-austin-robotaxi-fleet-hits-10-unsupervised-model-ys
5. Wikipedia: Tesla Cybercab production commenced April 2026. https://en.wikipedia.org/wiki/Tesla_Cybercab
6. TechCrunch: Waymo 500K paid rides/week across 10 U.S. cities, March 2026. https://techcrunch.com/2026/03/27/waymo-skyrocketing-ridership-in-one-chart/
7. Electrek: Hyundai in talks to supply Waymo 50,000 IONIQ 5s by 2028 (~$2.5B deal). https://electrek.co/2026/02/11/hyundai-supply-waymo-50000-ioniq-5-robotaxis/
8. ARK Invest: Tesla Cybercab ~50% cheaper per mile than Waymo Gen 6; fleet to ~7,200 by end 2026. https://www.ark-invest.com/newsletters/issue-496
9. Grand View Research: Global AV market $86B (2025), projected $214B by 2030. https://www.grandviewresearch.com/industry-analysis/autonomous-vehicles-market
10. IEEE: LLM-driven Multi-vehicle Dispatching and Navigation (LiMeda) framework. https://ieeexplore.ieee.org/iel8/10609961/10609862/10610578.pdf
