# Àdìrè Vibes (LHIS End of Year Thanksgiving)

Static site. No build step. Vercel: Framework Preset "Other", leave build settings empty.

## Files
- index.html: the site (you should not need to touch this)
- data.json: ALL the words, budget lines and donors live here
- flyers/: the three flyers (replace a file with the same name to change a flyer)
- og2.jpg: the WhatsApp preview picture

## How to change the words
1. Open data.json (on github.com: click the file, then the pencil icon).
2. Find the line you want. Everything under "text" is a sentence on the site.
3. Change ONLY the words between the quote marks. Keep the quote marks and the comma at the end.
   If you need an apostrophe use ’ so you do not break the quotes.
4. Commit changes. The site updates in about a minute.

Where things are:
- "config": the title, the teaser line under it and the countdown date
- "text": every other sentence and label. {pct} is filled in with a percentage automatically, leave it in.
- "activities": the cards in each party section. Each card is [emoji, title, small line].
- "sections": the budget lines. "budget" is the amount, "group" is both, adults, kids or teens.
  Set "pending": true and "budget": 0 to show a line as Pending.
- "donors": the Wall of Stars. Copy a donor line, give it a new unique "id", the name, the amount and a bigger "ts" number.
