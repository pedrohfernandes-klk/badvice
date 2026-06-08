BADVICE

Terrible ideas, beautifully stated.

BADVICE is a one-button satire machine for recognising polished bad behaviour: soft threats, elegant excuses, office knives, fake maturity, healing-language getaways, and tiny cruelties dressed as wisdom.

Press the button. Receive a piece of terrible advice. Do not follow it.

Use it to notice the trick.

WHAT IT IS

BADVICE is a self-contained browser app built as a single HTML file.

It contains a curated deck of 999 cards. Each card is a short satirical line of “advice” that exposes manipulative, evasive, cowardly, selfish, or socially polished behaviour by making it sound almost reasonable.

The joke is diagnostic: the advice is bad, but the pattern is recognisable.

CURRENT STATUS

App: BADVICE
Deck size: 999 cards
Format: single-file HTML
Mechanism: one-button random card draw
Storage: local browser only
Backend: none
Build step: none
Version status: expanded 999-card deck

CORE INTERACTION

The app has one primary action:

MAKE IT WORSE

Each press selects a random card from the internal deck and displays it on the BADVICE slip.

Secondary controls:

COPY copies the current card text.

CLEAR resets the display.

ABOUT opens the diagnostic/about panel.

INTENDED USE

BADVICE is useful for satire, creative prompts, pattern-spotting, writing exercises, social observation, dialogue sparks, bad-draft generation, and recognising manipulative language.

It is not a self-help tool.

It is not advice.

It is a machine for noticing how bad advice disguises itself.

CONTENT PRINCIPLE

A good BADVICE card should sound like something a person could almost say seriously.

The ideal card has three parts:

A recognisable social behaviour.

A polished or plausible justification.

A sting that reveals the poison.

Example:

Call neglect boundaries. It gives disappearance a front gate.

The tone should be sharp, plain, and readable. Avoid randomness for its own sake. Avoid cards that are merely silly, vague, decorative, or over-explained.

Each line should feel socially recognisable before it becomes poisonous.

STYLE RULES FOR FUTURE CARDS

Keep the language concise.

Make the behaviour recognisable.

Let the second sentence sharpen the first.

Prefer plain words over clever fog.

Avoid over-cute surrealism unless it reveals a real pattern.

Avoid generic motivational parody.

Avoid advice that is only “bad” because it is absurd.

Avoid repeating existing structures too often.

Do not soften the satire into normal advice.

Do not make the cards sound like slogans.

The best cards should feel like a social knife someone tried to wrap in nice paper.

GOOD CARD TEST

Before adding a new card, ask:

Could someone almost believe this?

Does it expose a real social pattern?

Is the second sentence doing useful work?

Is the image sharp but not distracting?

Would the card still work if read aloud?

Is it funny because it is accurate, not because it is random?

Would it make someone recognise a behaviour they have seen?

FILES

The app can be used as a standalone file:

index.html

It can also be placed inside a folder on a static site:

badvice/index.html

No extra files are required.

DEPLOYMENT

BADVICE is static.

To publish it, upload the HTML file to any static web host or to a folder inside an existing website.

Recommended structure inside the SPARK TOOLS site:

spark-tools/
badvice/
index.html

Then the live path should be:

/spark-tools/badvice/

The app does not require a database, server code, package manager, build tool, or installation step.

UPDATING THE DECK

The deck lives inside the JavaScript array named CARDS.

Each card has two fields:

theme
text

A card should follow this structure:

theme: a short label for the pattern
text: the full BADVICE line

After adding cards, check that:

The total card count is correct.

There are no duplicate card texts.

Every card has both theme and text.

The JavaScript still passes syntax checking.

The ABOUT counter reflects the current deck size.

The app still loads, draws cards, copies text, clears text, and opens the ABOUT panel.

FINAL NOTE

BADVICE works because it does not shout “this is bad”.

It lets the bad idea speak in its best clothes.

Then it makes the clothes look suspicious.
