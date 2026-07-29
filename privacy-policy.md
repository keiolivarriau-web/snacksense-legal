# SnackSense — Privacy Policy

**Version:** [set on publication — must equal `LEGAL_VERSION` in `lib/legal/version.ts`] · **Effective date:** [set on publication]

This policy explains what SnackSense collects, why, who processes it, and the choices you have. We've kept it plain.

## 1. Who we are

SnackSense ("SnackSense", "we", "us") is the app you use to turn what's in your kitchen into recipes.

The operator responsible for your data is **Yaeko Uehara Nagano**.

You can reach us about privacy, or to request deletion, at **snacksense.help@gmail.com**.

## 2. What we collect, and why

We collect only what the app needs to work. Each item below is tied to its purpose.

**Account and identity**

- Your **email address** and your **password** (stored hashed by our sign-in provider) — so you can have an account and sign back in.
- Or, if you use **Sign in with Apple** or **Sign in with Google**, the identity those services share with us — your **name and email** — so you can have an account without creating a separate password. (You choose whether to share your real email or Apple's private relay.)
- Your **display name** — to greet you in the app.

**Your profile and preferences**

- Your **goal** and any target, **dietary restrictions**, **allergies**, foods you avoid, cuisines, spice level, cooking ability, and taste preferences — so we can suggest recipes that fit you.
- Self-reported figures like your **food-spend and takeout baseline** — so we can estimate your savings.

**Your kitchen and cooking**

- The **ingredients** you scan or type, your **pantry staples**, meals you **plan** or mark as **cooked** (including the macros, calories, and goal recorded for a cooked meal), and recipes you **save** — so the app can build and track your recipes and progress.

**Apple Health / Health Connect (optional)**

- If you connect **Apple Health** (iOS) or **Health Connect** (Android), your **weight readings** and **workout sessions** — read **only with your explicit on-device permission**, and **read-only** — so we can show your progress next to the dinners you cook. We **never use this for advertising and never share it.**

**Basil (the in-app assistant)**

- Your **chat messages** with Basil — so it can answer you.

**Subscription**

- Your **subscription state** (trial or plan status and the identifiers our payment processor uses) — so we know what you have access to.

**How you use the app**

- **Product-usage events** — which screens and actions you use — **linked to your account** (not anonymous), so we can see where the product is failing people. If the app crashes, the **error message and technical details** are also collected. We do not use any of this for advertising and do not share it with advertisers or data brokers.

**Technical data collected automatically**

- Some of the tools built into the app collect technical data on their own: a **device identifier (IDFV)**, device model, operating-system version, locale/country, and app version (via our subscription tool); an anonymous analytics ID, screen size, and app build (via our analytics tool). Our servers and processors also record the **IP address** of your requests, and our analytics processor derives an approximate location from it.

**Voice**

- If you add groceries by voice, your speech is turned into text **on your device** — the **audio never leaves your phone**. The resulting **text** is processed like anything else you type (see section 4).

## 3. What we do NOT collect or keep

This section is as important as section 2.

- **We do not keep your scan photos.** When you scan your fridge, freezer, or a receipt, the photo is sent for ingredient detection and then discarded. We do not store it, and the app no longer uploads it to our storage.
- **We only read two things from Apple Health / Google Health Connect, and only if you connect them.** If you choose to connect, we read your **weight** and your **workouts** — nothing else (not heart rate, sleep, nutrition, or any other Health data). The connection is **read-only**: we never write anything back to Apple Health or Health Connect. You can disconnect at any time.
- **We do not store your date of birth.** During onboarding we ask it to check you're old enough (see section 7). It's used for that check in the moment, is never sent to our servers, and is not saved anywhere.
- **We do not track you across other apps or the web, and we show no ads.** There is no advertising software in the app, no attribution/ad-measurement software, and we never request the advertising identifier (IDFA). Apple's App Tracking Transparency prompt does not apply to us.
- **We do not register a push-notification token.** Reminders are handled locally on your device.

## 4. Who processes your data

We use a small set of service providers ("processors") to run SnackSense. They act on our instructions; **we do not sell your personal data, and there is no onward sharing for advertising.**

- **Supabase** — our database, sign-in, and hosting. It holds the account and app data in section 2. Servers are in the **United States**, and it records the request IP.
- **Railway** — hosts our API. Its logs may include your user ID and IP.
- **Anthropic** — receives **only your fridge / freezer / receipt-style scan photos**, to identify the ingredients in them. It does not receive your chats, your diet profile, or your voice. Under our commercial agreement these photos are **not used to train models**, and they are **retained only briefly for processing and abuse prevention**.
- **Google (Gemini)** — generates recipes and handles the other AI features. It receives what each feature needs: for recipe generation, your ingredient names, goal, and diet profile; for **Basil chat, your free-text messages** (and, in the in-recipe assistant, a diet summary that **includes your declared allergies**); for receipts, the receipt image; and the text from voice input. On our current paid tier, Google **does not use this to train its models**.
- **RevenueCat** — manages your subscription. It receives your user ID and purchase events, and its software collects the technical data noted in section 2.
- **PostHog** — our product analytics and crash reporting, keyed to your user ID, in the **United States**. It records IP and approximate location.
- **Superwall** — decides which subscription offers to show. It receives your user ID and a small set of account attributes (your plan and signup/cooking status — **not** your health goal). Its integration list is empty, so it **forwards your data to no one else**.
- **Apple and Google (in-app purchases)** — process your payment when you subscribe. They are independent of us; **we never see your card details.**
- **Apple and Google (Sign in with Apple / Google), if you choose them** — instead of an email and password, that service confirms who you are and shares your **name and email** with our sign-in provider to create your account. We receive nothing beyond name and email, and no password.
- **Apple Health (iOS) / Google Health Connect (Android)** — a source on *your own device*. With your permission, we **read** your weight and workouts from it (read-only) to show your progress in the app. This is not a company we hand your data to. Your Health data is **never used for advertising and never shared with anyone**, in line with Apple's HealthKit rules.

Because several of these providers are in the **United States**, your information may be processed there, wherever you live.

## 5. Consent

You accept this Privacy Policy and our Terms of Service by **ticking a box that must be checked before your account can be created — on every way you can sign up.** Whether you use email, **Sign in with Apple**, or **Sign in with Google**, the button that creates your account stays disabled until you tick it. When you accept, we record **which version you agreed to and when**.

## 6. Deletion, and your rights

You can ask us to delete your account at any time, by emailing us at the address in section 1. When you do, we **delete your account and the data linked to it**, and this cascades through all of our tables. We also send deletion requests to **RevenueCat** (your subscription record) and **PostHog** (your analytics record) so your data is erased there too.

A few things are kept on purpose, and you should know about them:

- A **de-identified record of promotional-offer redemptions and cancellation feedback** (with your user ID removed), so the "one promotional save per customer" limit can't be gamed by deleting and re-creating an account.
- **Payment records held by Apple or Google**, under their own policies.
- Our payment and analytics **processors retain data under their own retention policies.**

Depending on where you live, you may also have the right to **access, correct, or export** your personal data. You can edit most of it in the app, and you can email us to exercise these rights.

## 7. Children

SnackSense is **intended for people aged 13 and older**. During onboarding we ask your date of birth and you can't continue unless the date you choose meets that age. This is a **self-declared** check — we do **not** verify your age, and we do not keep a record of the date you entered. We do not knowingly collect data from anyone under 13; if you believe a child under 13 has given us data, email us and we'll delete it.

## 8. Changes to this policy

If we change this policy, we'll update the version and effective date above and, for significant changes, let you know in the app. The version you agreed to is recorded with your acceptance.

## 9. Contact

Questions or requests about your privacy? Email **snacksense.help@gmail.com**.
