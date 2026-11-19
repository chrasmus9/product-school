# Outcome Roadmap & Trade-off Memo: Fable Growth

> Module 2 · Turn Your Strategy into an Outcome Roadmap

## 1. Trade-off memo

> **Rock 1:** Fix the notification system (wrong times, timezone bug) (supports KR2): The plan only works if the reminder arrives at the right time before the event. Right now reminders come at the wrong time, so people miss steps and don't finish their plan.
>
> **Rock 2:** Redesign the onboarding flow based on 40% drop-off data (supports KR1): In the new onboarding, we ask "what's coming up in your life?" on day one. More people add an event early, and fewer drop out before they see the value.
>
> **Rock 3:** Add AI-generated daily check-in prompts personalized to user history (supports KR3): We keep the personal part, but drop the daily part. About once a month, a short prompt asks if anything big is coming up. In the weeks before an event, the prompts follow the plan and use what helped the person last time. This gives people a reason to keep paying between big events.
>
> **Hard no 1:** Create a “crisis mode” flow for acute anxiety moments: It pulls Fable back to the moment of crisis, when our strategy is about the time after. It also moves us toward clinical care, which we are not allowed to do.
>
> **Hard no 2:** Build a social layer: share your progress with friends: People sharing mental-health struggles needs constant watching and can go wrong. It would take a big part of our 14 people, and it does not help anyone get ready for a life event.
>
> **Hard no 3:** Localize the app into Spanish and Portuguese: It brings in new users in new markets. First we need to keep the users we have. Translating all our audio content is also a big job.

## 2. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | The problem: people stop using Fable once they feel better. We bet fixing reminder timing will get more people to finish their plan for users with an upcoming event (KR2); We bet asking "what's coming up in your life?" during onboarding will get more people to add an event early for new paying users (KR1); We bet a short monthly check-in, built on what helped each person before, will keep people paying between big events for users who feel better (KR3) | Engineering, Product; Design, Product, Engineering; Product, Engineering, Content, Clinical advisory | Reminders arrive at the right local time, and plan completion rises toward 6 in 10; onboarding drop-off falls below 40%, and more users add an event in month one; at least half of users answer the monthly check-in, and 6-month retention starts rising from about 30% |
| Next (3 to 6 mo) | Plans for the five most common events (new job, new baby, moving, exams, dark winter months), because we first need to see which events people actually add; A short "did you feel ready?" question after each event, because we need finished plans before we can ask; Let users connect their calendar to spot events, once we know people add events by hand; A seasonal message to past users before winter, once reminders work reliably; Faster app and the accessibility fixes, because they're needed but don't move an OKR | Content, Clinical advisory; Product; Engineering; Product, Content; Engineering | Each event plan has a completion rate we can compare; 7 in 10 say they felt ready; more events added per user; past users come back before winter; load time under 2 seconds and the accessibility audit gap closed |
| Later (6 to 12 mo) | Bet: reminders and short breathing exercises on Apple Watch before an event; Bet: plans for two people going through the same event, like a couple expecting a baby (shared plans, no public feed); Bet: Spanish and Portuguese, but only once retention reaches 45% | Engineering, Design; Product, Design, Clinical advisory; Content, Product | Watch users finish more of their plans; couples finish plans more often than individuals; new markets keep users as well as existing ones |
