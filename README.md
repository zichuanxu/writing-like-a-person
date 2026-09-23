# Writing like a person

A style reference for LLMs and writing agents. Read it once before drafting anything that should sound like a human wrote it, work from sections 4 to 6 while revising, and run the checklist in section 11 before handing a draft back.

Contents: 1. What this guide can and can't do · 2. Three principles · 3. Pick the register first · 4. What gives AI text away · 5. Fake-human tells · 6. What to do instead · 7. Don't invent facts · 8. Register presets · 9. Workflow · 10. Before and after · 11. Final checklist

## 1. What this guide can and can't do

Readers and AI detectors pick up on machine-written text for mostly the same reason: it's too smooth. The word choices are the most likely ones, the sentences are all about the same length, every point gets equal weight, and nothing in it is specific enough to belong to one particular writer. Human writing is lumpier. It has opinions, real details, uneven rhythm, and a few rough edges.

Some honest limits before the rules:

- Nothing guarantees a low or zero score. Detectors are probabilistic; they often disagree with each other, and they flag plenty of text that people wrote themselves. Formulaic writing and writing by non-native English speakers get flagged at noticeably higher rates. OpenAI shut down its own detector in 2023 because it wasn't accurate enough.
- Surface tricks mostly backfire. Planted typos, swapping words for rarer synonyms, and running text through "humanizer" paraphrasers usually make the writing worse, and many current detectors are trained classifiers that look at far more than individual words.
- What does work is the same stuff that makes writing good: specific content, a clear point of view, natural rhythm, and fewer of the habits listed in sections 4 and 5.
- The biggest single improvement comes from a real person: one true detail, one opinion, one thing that actually happened. If you can ask the user for those, ask.

### How text gets flagged

- Predictability. Many detectors estimate how easy each next word is to guess. Model output leans on high-probability words, so it scores as very predictable (low "perplexity").
- Uniformity. People swing between short and long sentences, and between simple and dense passages. Model output stays level (low "burstiness").
- Style fingerprints. Classifier-based detectors learn the vocabulary, sentence patterns, and formatting that show up far more often in AI text. Most of them are listed in section 4.
- Readers do all of this by feel. Once someone spots "delve" and three em dashes in one paragraph, they stop trusting the rest.

## 2. Three principles

### Common words, uncommon content

Plain vocabulary is good. Predictable content isn't. The surprise in a sentence should come from what it says (a number, a name, a small observed detail, an actual opinion), not from rare words.

"Regular exercise is important for maintaining good health" uses simple words and says nothing, so every word is easy to guess. "I walk to the station and back, 22 minutes each way, and that's about the only exercise I get" uses words just as simple, but no model would predict where it's going.

### Uneven on purpose

Vary sentence length, paragraph length, section length, and how much attention each point gets. Real writers spend three paragraphs on the thing they care about and one line on everything else.

### Somebody is talking

Every piece has a writer with a position, talking to a particular reader. Take a side. Admit downsides. Leave out what doesn't matter to this reader.

One rule sits above all three: no technique should turn into a habit. A move used once reads as voice. The same move used five times is a pattern, and patterns are exactly what readers and detectors catch.

## 3. Pick the register first

Decide how formal the context is before writing. Most of the rules below flex with it.

| Register | Typical contexts | Contractions | Fragments | Starting with And / But / So | gonna, kinda | Comma splices |
|---|---|---|---|---|---|---|
| Casual | Texts, DMs, chat, comments, forum replies | Always | Often | Often | Fine | Fine |
| Conversational | Blog posts, newsletters, social posts, most marketing copy | Almost always | Sometimes | Yes | Rarely | No |
| Friendly professional | Work email, support replies, landing pages | Yes | Now and then | Yes | No | No |
| Formal | Reports, policies, investor and legal documents | Sparingly | No | Occasionally | No | No |

Model defaults usually land a notch more formal and more polished than what a person would write in the same spot. When unsure, go one step more relaxed than your first instinct, unless the context really is formal.

## 4. What gives AI text away

### 4.1 Vocabulary

These words show up far more in model output than in human writing. One on its own won't sink a piece. Three in a paragraph will. (Literal meanings are fine: "landscape" for a painting, "journey" for an actual trip, "navigate" for a ship.)

- Verbs: delve, embark, navigate, leverage, utilize, harness, foster, bolster, underscore, showcase, streamline, elevate, empower, unlock, unleash, revolutionize, resonate, spearhead, facilitate, enhance, optimize, cultivate, ensure, boast
- Adjectives: pivotal, crucial, vital, paramount, robust, seamless, comprehensive, holistic, dynamic, vibrant, intricate, meticulous, nuanced, multifaceted, innovative, transformative, cutting-edge, state-of-the-art, ever-evolving, invaluable, noteworthy, commendable, unparalleled, bustling, breathtaking
- Nouns: landscape, realm, tapestry, journey, testament, beacon, symphony, labyrinth, treasure trove, cornerstone, synergy, game-changer, deep dive, ecosystem (outside tech)
- Quantity words: myriad, plethora, a wide array of, a diverse range of, numerous, various
- Adverbs: seamlessly, effortlessly, meticulously, notably, importantly, ultimately, undeniably, essentially

Plain swaps, plus something better than the swap where there is one:

| Instead of | Try | Better still |
|---|---|---|
| utilize, leverage | use | say what it's used for |
| facilitate | help, make easier | say what gets easier |
| numerous, a myriad of | many, a lot of | the actual number |
| in order to | to | |
| prior to, subsequently | before, then | |
| approximately | about, around | |
| demonstrate, showcase | show | |
| ascertain | find out, check | |
| individuals | people | who, exactly |
| purchase, obtain | buy, get | |
| regarding | about | |
| therefore, thus | so | |
| however (to open a sentence) | but | |
| additionally, furthermore, moreover | also, plus, and | often nothing at all |
| require, possess | need, have | |
| enhance, optimize | improve | by how much: "load time went from 4 seconds to 1" |
| implement | set up, roll out, start using | |
| pivotal, crucial | important, big | why it matters |
| robust | solid, sturdy | what it survives: "took a fall onto tile" |
| seamless | smooth | what the user doesn't have to do: "no second login" |
| foster | build, encourage | |
| landscape, realm | market, field, world | |
| a testament to | shows, proves | |
| boasts | has, comes with | |
| vibrant | lively, busy | what's actually there |

Phrasal verbs are one of the quickest ways to sound native. English speakers reach for them constantly. Model text (and a lot of non-native text) reaches for the single Latin-root verb instead.

| Stiff | Natural |
|---|---|
| determine | figure out, work out |
| establish | set up |
| investigate | look into |
| encounter | run into, come across |
| postpone | put off, push back |
| discover | find out |
| tolerate | put up with |
| reduce | cut down on, cut back |
| eliminate | get rid of, cut out |
| review | go over, look over |
| devise | come up with |
| resolve | sort out |
| abandon | give up on |
| compensate for | make up for |
| continue | keep going, keep at it |

Two ways to overcorrect:

- Don't dumb down terms the reader actually uses. A developer says "API" and "latency." A nurse says "triage." Swapping real jargon for a vague paraphrase sounds as fake as "delve."
- Don't cycle synonyms. Models avoid repeating a noun, so they rotate through "the company... the firm... the organization... the brand." People just say "the company" again. Repeat the word.

### 4.2 Stock phrases

Openers:

- "In today's fast-paced world," "In today's digital age," "In the ever-evolving landscape of..."
- "When it comes to..."
- "Have you ever wondered...," "Imagine a world where...," "Picture this:"
- "Let's dive in," "Let's explore," "Let's break it down"
- "X is more than just Y"
- "Great question!" "Certainly!" "Absolutely!"
- "I hope this email finds you well"

Start with the substance instead: the answer, a specific fact, a small scene, or a claim. If you can delete the first sentence and lose nothing, leave it deleted.

Transitions and filler:

- "Additionally," "Furthermore," "Moreover," "Notably," "Importantly," "Consequently," "In essence"
- "It's important to note that," "It's worth mentioning that," "It's crucial to remember"
- "plays a crucial role in," "a wide range of," "in terms of," "the fact that"

Most of these can just go. Where a link is needed, "and," "but," "so," "also," "plus," "still," "anyway," or "that said" will do the job.

Essay clichés:

- pave the way, shed light on, strike a balance, a double-edged sword, stand the test of time, only time will tell, the tip of the iceberg, a perfect blend of

Closers:

- "In conclusion," "In summary," "Overall," "Ultimately," "At the end of the day"
- "By following these tips, you can..."
- "Remember, ...," "The possibilities are endless," "The future of X is bright"
- "Happy baking!", "Happy planning!" and the rest of that family
- "I hope this helps!", "Feel free to reach out if you have any questions," "Please don't hesitate to contact us"

Stop when you're done. End on the last useful thing, like a next step, a concrete detail, or a short opinion. Skip the recap unless the piece is long enough that a reader actually needs one.

Marketing puffery:

- "unlock the full potential," "take your X to the next level," "elevate your experience"
- "seamless integration," "cutting-edge," "state-of-the-art," "revolutionary," "game-changer"
- "tailored solutions," "curated," "designed with you in mind," "look no further," "a must-have"
- "whether you're a seasoned pro or just starting out"
- "nestled in the heart of," "boasts," "stunning," "immerse yourself," "unparalleled"

### 4.3 Sentence patterns

- Contrast framing: "It's not X, it's Y." "This isn't about X. It's about Y." "Not only X, but also Y." Once per piece at most, and only when somebody actually believes X.
- Reflexive threes: "fast, reliable, and affordable." Models group things in threes by default. Use two, or four, or just the one that matters.
- The -ing tail: a sentence that ends with a comma and a participle adding commentary. "..., highlighting the importance of teamwork." "..., reflecting a broader shift in consumer habits." "..., ensuring a smooth experience." Cut the tail, or turn it into its own sentence that makes a real claim.
- "Serves as," "stands as," "acts as" when you mean "is."
- Inflated significance: "plays a pivotal role," "marks a significant milestone," "a testament to."
- Question reveals: "The result? A 40% drop in returns." "The best part? It's free." Fine once in a long piece. As a habit, it's a tell.
- "Whether you're a beginner or a seasoned pro, ..."
- "From X to Y, ..." as in "From busy parents to small business owners, ..."
- Colon setups: "Here's the thing:" "Here's why:" "The bottom line:"
- Vague attribution: "Experts say," "Studies show," "Many people believe." Name the source or drop the claim.
- Stacked hedges: "may potentially help," "could possibly be." One hedge at most, and only where the writer really isn't sure.
- The same sentence opening three times in a row: "This... This... This..."

### 4.4 Structure and formatting

- The school-essay template: an intro that restates the question, three body sections of equal size, and a conclusion that restates the intro.
- Every paragraph three or four sentences long, each ending on a tidy summary line.
- Headers on a 400-word blog post or an email.
- Bulleted lists where every item opens with a bold label ("**Speed:** ...").
- Bold sprinkled through ordinary paragraphs.
- Title Case On Every Heading. Sentence case looks more natural in most modern writing.
- Titles built as "Big Idea: A Comprehensive Guide to Something."
- Emoji used as bullets or section markers, unless that really is the platform's norm.
- Markdown where people type plain text: email, chat, support replies, social posts.
- Perfect symmetry: every section with exactly three points, every list item the same length.
- Em dashes. They're one of the best-known tells right now. Default to none, and use a period, comma, parentheses, or colon instead.

### 4.5 Content

- Generic claims that could be about anything: "Quality matters." "Communication is key."
- Relentless positivity. No downsides, no friction, no "the catch is."
- Both-sides mush: laying out considerations without ever picking one.
- Equal weight on every point.
- Explaining what the reader obviously already knows.
- Sections nobody asked for, like an FAQ or "Key takeaways."
- No names, numbers, places, times, prices, or sensory details anywhere.
- Leftover chatbot voice: "Certainly! Here's a revised version," "As an AI," "Let me know if you'd like me to adjust the tone," or notes about the draft pasted into the final text.

## 5. Fake-human tells

Models told to "sound human" or "be casual" tend to slide into a second set of habits. Readers spot these just as fast now.

- "Honestly?" "And honestly? That's okay."
- "Here's the thing." "Let's be real." "Real talk:" "Plot twist:" "Spoiler alert:"
- "Let that sink in."
- Stacks of one-line paragraphs for drama (the LinkedIn staircase).
- "No fluff. No filler. Just results."
- Punchy fragments every other line. "Simple. Fast. Done."
- Slang the writer wouldn't use in this situation.
- Planted typos, a sudden lowercase line, or a "lol" dropped into otherwise polished text.
- Replacing every em dash with a semicolon. The usual fix for an em dash is a period.
- "I'm no expert, but..." followed by an expert-sounding essay.

The target isn't "casual." It's natural for this writer, in this situation, talking to this reader.

## 6. What to do instead

### 6.1 Rhythm

- Mix sentence lengths hard. Some sentences should be three to six words. Some should run past 25, with a clause or two trailing off the end, the way people talk when they're explaining something they care about.
- A quick check: in any paragraph of four or more sentences, have at least one under 8 words and at least one over 20.
- Vary paragraph length too. A one-line paragraph now and then. A long one when the idea needs room.
- Vary how sentences start.

### 6.2 Informal grammar that native speakers actually use

These break school rules, but they're completely standard in real English:

- Contractions: it's, don't, you'll, we've, that's, wouldn't. "Do not" reads stiff in casual text unless it's for emphasis ("Do not plug it in yet").
- Starting sentences with And, But, So, Or, or Because.
- Ending on a preposition: "That's the part I'm worried about." "What's it for?"
- Fragments. For emphasis, now and then.
- "Who" instead of "whom," except in formal writing.
- Singular "they."
- Split infinitives: "to really understand."
- Comma splices, in casual writing only: "It's late, I'm heading home."
- Gonna, wanna, kinda, gotta: texts and chat only.
- Parentheses for asides. People use them a lot more than models do (and em dashes a lot less).
- Exclamation marks: one or two is normal in friendly writing. None in formal writing.

About deliberate mistakes: don't manufacture them. Real people make typos, but a planted one in a landing page or a work email costs more credibility than it could ever buy, and detectors don't depend on spelling anyway. The exception is very casual text (texts, chat replies), where a lowercase start or a missing period is just how people type.

### 6.3 Words that carry voice

- Hedges people use: I think, probably, pretty ("pretty good"), a bit, kind of, not sure, as far as I can tell. Use them where the writer really is unsure, not as padding.
- Intensifiers: really, way ("way better"), so ("so much easier"), actually, super (casual only).
- Linking words: anyway, still, that said, plus, to be fair, "oh, and."
- Conversational set phrases, one or two per piece, when they fit: worth a shot, a pain, hit or miss, for what it's worth, a no-brainer. These are different from the essay clichés in section 4.2, and stacking them ("at the end of the day it's a win-win that moves the needle") is its own tell.

### 6.4 Specificity

This matters more than anything else here.

- Replace generic claims with specific ones from the source material.
  - "Fast shipping" → "Orders placed by 2 p.m. ship the same day."
  - "Saves time" → "Our weekly report went from three hours to about 40 minutes."
  - "Easy to set up" → "Plug it in, scan the code on the bottom, and you're done. It took me about five minutes."
- Use numbers, names, places, times, prices, and durations.
- Include one small detail a person would only know from being there or using the thing.
- Quote something someone actually said, if you have it: "My manager's entire review was 'fine, ship it.'"
- Mention a downside, a limit, or some friction. "The app is solid. Pairing it took two tries, though." Admitting one flaw makes everything else more believable.

### 6.5 Point of view

- Have an opinion and say it. "Get the smaller one. The big one isn't worth the extra $80 unless you print every day."
- Spend words where the writer cares and skim the rest.
- Write to one reader. "You" is fine. "I" and "we" are fine when there's a real person or team behind the text.
- Not every paragraph needs a neat ending. Once in a while, let a point just sit there.

## 7. Don't invent facts

Specific details are the strongest human signal, which makes them tempting to fake. Don't.

- Take details from the brief, the source documents, or the user. If the piece needs something you don't have (a figure, a customer story, a first-person experience), ask for it or write around the gap.
- Never present made-up statistics, quotes, reviews, testimonials, or personal experiences as real. It misleads readers, and it's the kind of thing that lands a brand in legal trouble.
- Clearly labeled samples and mockups (example reviews for an internal style doc, a practice email for training) can use invented details. Make them realistic, with concrete numbers and situations rather than bracketed placeholders, and keep them consistent with the real product facts: price, what's in the box, how long setup takes, how long the free trial lasts.

## 8. Register presets

### Casual: texts, DMs, chat, comments

- Short. Often no greeting or sign-off.
- Lowercase and missing periods are fine where that's how people type on the platform.
- Contractions always. Fragments and comma splices are normal.
- No headers, bullets, or bold.

> ok just checked, the 3:40 train got cancelled. taking the 4:10 instead, should be there around 5

### Blog posts, newsletters, articles

- Open with the point or a concrete moment, not a definition or a line about "today's world."
- First person is fine if there's a real author.
- Headers only if the piece is long (roughly 1,000 words or more) and people will skim. Sentence case.
- Mixed paragraph lengths. A few one-liners, not a staircase of them.
- End on something useful or a final opinion, not a summary.

### Marketing and landing page copy

- Say what the product does for the reader in plain words, with a number if there is one.
- Specific beats superlative: "Fits a 16-inch laptop and two days of clothes" beats "spacious and versatile."
- Name the obvious objection and answer it: "Yes, it works offline."
- Short lines and some fragments are fine here. Not every line, though.
- One call to action, stated plainly: "Start your 30-day trial," not "Embark on your journey today."

### Work email

- A subject line that says what's inside.
- Get to the point in the first line.
- One ask, stated clearly, with a date if there is one.
- Sign off with "Thanks," or just your name.

### Customer support replies

- Say what happened and what you're doing about it in the first two lines.
- Use the customer's name once, and repeat their details back (order number, the model they mentioned).
- One specific apology ("Sorry the box showed up crushed"), not a paragraph of regret.
- Give the next step and when it'll happen.
- Skip "We understand your frustration" and "We value you as a customer."
- Sign with a person's name, not "The Support Team."

### Formal reports and professional documents

- Contractions sparingly. No slang, few fragments.
- The tells in sections 4 and 5 still apply. Formal doesn't mean ornate, so cut the filler transitions, hedges, and inflated significance here too.
- Numbers and named sources carry the credibility.
- Headings and tables are fine, since readers use them to find their way around.

## 9. Workflow

Before drafting:

1. Who's reading, where, and in what mood? Pick the register from section 3.
2. Collect the specifics: names, numbers, dates, prices, product facts, quotes, stories. If the brief has none, ask for two or three before you start.
3. Decide the one thing the piece has to say, and what the writer thinks about it.

Drafting: write it the way the writer would say it to one person across a table. Don't polish yet.

Revising, in this order:

1. Cut. Delete a throat-clearing first sentence, a recap ending, filler transitions, and extra hedges.
2. Vocabulary. Scan for the words and phrases in section 4 and replace them with plain words or, better, with specifics.
3. Specificity. Find every generic claim. Swap in a real detail from the source, or cut the claim.
4. Rhythm. Check sentence and paragraph lengths, break up runs that are all the same, and vary how sentences start.
5. Structure. Remove headers, bullets, and bold the context doesn't need. Break the symmetry.
6. Say it out loud. Would this writer actually say each sentence? Rewrite anything that sounds like a brochure or a textbook.
7. Check facts. Every number, name, and claim should trace back to the brief or source. Nothing invented unless it's a labeled sample.

## 10. Before and after

The details in these examples are assumed to come from the brief or the writer. In real work, don't make them up.

### Blog opening

Before:

> In today's fast-paced world, time management has become more important than ever. Whether you're a busy professional or a student juggling multiple responsibilities, finding effective strategies can be a game-changer. In this article, we'll delve into five proven techniques to help you unlock your full potential.

After:

> Every Sunday night I used to plan my week in a color-coded spreadsheet. By Tuesday it was fiction. What finally stuck was a lot dumber: one sticky note with three tasks on it, rewritten every morning while the coffee brews. I've done it for about a year. It falls apart on travel weeks, but it beats the spreadsheet, and I think I know why.

The rewrite opens on a real moment instead of a stock line, uses concrete details, admits one weakness, and its sentences range from 5 words to 22.

### Product copy

Before:

> Elevate your coffee ritual with our cutting-edge burr grinder. Meticulously engineered for precision, it seamlessly delivers the perfect grind every time, unlocking the rich, nuanced flavors of your favorite beans. Whether you're a seasoned barista or just starting your coffee journey, it's the ultimate must-have.

After:

> A hand grinder that does a medium grind for one cup in about 40 seconds. The steel burrs adjust in 30 clicks, from espresso-fine to coarse enough for a French press, and it's quiet enough to use at 6 a.m. without waking anyone. The catch is espresso. Grinding that fine takes real arm work, closer to two minutes, so if you drink espresso every day, get an electric one.

Numbers replace adjectives, there's one real use scene, and it tells some readers not to buy it.

### Work email

Before:

> Subject: Following Up
>
> Dear Sarah,
>
> I hope this email finds you well. I wanted to follow up on our meeting last week regarding the Q3 marketing initiatives. As discussed, it is crucial that we align on key deliverables to ensure seamless execution. Please don't hesitate to reach out if you have any questions.
>
> Best regards,
>
> Tom

After:

> Subject: Q3 banner: need your pick by Friday
>
> Hi Sarah,
>
> Thanks for Thursday. The one thing we didn't settle was which banner runs in July, the blue one with the price up front or the photo version. Design needs an answer by Friday to make the July 3 launch.
>
> I'd go with the blue one. A similar layout got about 12% more clicks in the spring test, and it's easier to translate.
>
> Tom

The subject line says what's needed, there's no filler at either end, there's one ask with a deadline, and the writer gives an opinion with a reason.

### Support reply

Before:

> Dear Valued Customer,
>
> Thank you for reaching out. We sincerely apologize for any inconvenience this may have caused. We understand how frustrating it can be when an order doesn't arrive as expected. Rest assured, our team is working diligently to resolve this issue. Please allow 5-7 business days for further updates.
>
> Best regards,
>
> Customer Support Team

After:

> Hi Daniel,
>
> Sorry about this one. Order #48213 got stuck at the Columbus depot because the address was missing your apartment number. I've added "Apt 4B," and the carrier has it moving again, so it should reach you Thursday.
>
> If it isn't there by Friday, just reply here and I'll send a replacement right away. No need to return anything.
>
> Jess

It uses the customer's name and order details, says what went wrong and what's been done, gives a date plus a fallback, and it's signed by a person.

### Over-corrected vs. natural

Trying too hard to sound human:

> Let's be real. Meal prep? Overrated.
>
> Here's the thing.
>
> Most people quit by week two. Why? It's boring.
>
> No fluff. No gimmicks. Just food you'll actually eat.
>
> And honestly? That's the whole point.

Natural:

> I gave up on Sunday meal prep after about three weeks. Five days of the same chicken and rice got old fast. Now I cook double on Mondays and Wednesdays and eat the leftovers for lunch the next day. It's half the work, and I don't dread lunch anymore.

No fake-casual tics and no staircase. Just one person describing what they actually do.

## 11. Final checklist

- [ ] The first sentence says something specific. No stock opener.
- [ ] No recap ending, no "hope this helps," no "feel free to reach out."
- [ ] Few or none of the words in section 4.1.
- [ ] Contrast framing once at most. No reflexive threes. No -ing commentary tails.
- [ ] No em dashes (or one that really earns its place).
- [ ] Sentence lengths vary. Most paragraphs have something under 8 words and something over 20.
- [ ] Paragraph lengths vary.
- [ ] Concrete details throughout: numbers, names, places, times, things observed.
- [ ] The writer takes a position somewhere.
- [ ] At least one honest limit, trade-off, or downside, where the context allows it.
- [ ] Formatting matches what a person would do here. No headers, bold, or bullets in email, chat, or support replies.
- [ ] Contractions fit the register.
- [ ] None of the fake-casual tics from section 5.
- [ ] Every fact traces back to the brief or source. Nothing invented, except in labeled samples.
