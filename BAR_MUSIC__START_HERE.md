# Bar music: the starter pack

Put this file into a Claude project and Claude will walk you through the whole thing, one step at a
time, from where you are now to music that runs itself, changes through the day, never plays the same
day twice, holds its volume, and tells you when it has gone quiet.

You do not need to know anything about computers to start. Read Part One, do the three steps, then
let Claude take over.

---

# PART ONE: FOR YOU. Do this first, then stop

## Why you are here, and what you will get

You already use Sonos alarms, so you already know their ceiling. An alarm plays one playlist, at one
time, at one volume. It plays the same thing every day, it does not stop a bartender cranking it, it
restarts the moment someone turns it off, and when it fails it just goes silent and you find out from
a customer. This pack builds the thing that fixes all four:

- **A different playlist each day**, rotated, so staff are not hearing the same forty songs for
  months.
- **A volume ceiling** per part of the day, eased back down if someone turns it up and forgets.
- **Respect for a manual off**: turn it off by hand and it stays off until the next change of the day.
- **A warning when it breaks**, instead of a quiet room nobody notices until service.

## What a "project" is, in one paragraph

A project is a folder inside Claude that remembers. Anything you put in it, Claude can see in every
chat you start inside that folder. Without it, every new chat starts from nothing and you re-explain
your bar, your speakers and what you already did. With it, you can stop halfway, come back three days
later, start a new chat, and carry on where you left off.

**Projects need a paid Claude plan.** If you do not see Projects in the menu, that is why.

## Step 1: make the project

1. On a computer, open your web browser (Chrome, Safari, Edge or Firefox) and go to **claude.ai**.
   Sign in.
2. On the left side of the screen, click **Projects**. If you do not see it, click the three-line
   menu button at the top left to open the sidebar first.
3. Click **New project** (top right).
4. Where it asks for a name, type: **Bar music**
5. Click **Create project**.

## Step 2: put this file into it

1. Save this file somewhere you can find it, like your Desktop or Downloads.
2. On the project page, find the panel for adding files. It is usually on the right and says **Add
   content**, **Project knowledge**, or has a **+** on it. Click it.
3. Choose **Upload file** (or drag this file onto the page).
4. Wait for it to show up in the list. That is it. It is in.

## Step 3: start the first chat

Still inside the project, click into the message box at the bottom and type exactly this:

> Read the bar music starter pack in this project and start me at the beginning. I know nothing
> about any of this. Ask me one question at a time.

Send it. From here on, Claude is running it and you answer questions and press buttons.

## Optional, but it makes the GitHub part much easier: let Claude press the buttons

Out of the box, Claude can only tell you what to click. If you install the **Claude in Chrome**
extension for the Chrome browser, Claude can also do the clicking on websites for you while you
watch: open github.com, press "Use this template", find the Settings page, open the box for a
secret, fill in the boxes that are not secret. You approve each thing as it goes.

To get it: in Chrome, search the Chrome Web Store for **Claude in Chrome**, add it, and sign in to
it with the same Claude account. Then tell Claude at the start: "I have Claude in Chrome, do the
clicking for me where you can."

Two things it will never do, on purpose, and you should not ask it to: **type a password, key or
secret**, those are always you, and **use the Sonos app on your phone**, which has no website. So
the phone stages are still yours. Everything on github.com and developer.sonos.com, Claude can
drive.

If you do not want to install anything, skip this. Everything in the file works by you clicking.

## The one thing to remember

**If Claude ever tells you to do something and you do not know how, say so.** Type this:

> I don't know how to do that. Give me the exact buttons to press.

That is not a stupid question and it will not slow anything down. A step you cannot follow is a badly
written step, not a failure on your part. Say it every time it happens.

## What this will cost you in time

| Part | How long | What you get |
|---|---|---|
| A two-minute test that decides if this is even possible for your bar | Two minutes | A yes or no before you invest anything |
| Deciding what the bar should sound like through the day | One conversation, about 30 minutes | The plan |
| Building and saving the playlists | An evening, or ten minutes if you have them | The music |
| Wiring it up so it runs itself and rotates | A weekend, spread over a few sittings, with Claude | Music that runs itself forever |
| Being told when it breaks | Built in, no extra work | You hear about a silent bar before a customer does |

This is a weekend of work spread over a few evenings, not one sitting. That is honest. It was built
once already, by someone comfortable with this, and it took a few long evenings because things went
wrong that nobody could have predicted. With Claude holding your hand every step, it is all doable
and none of it needs you to understand code. Do it in pieces and stop when you are tired.

---

---

# PART TWO: FOR CLAUDE. How to run this

Everything below this line is written for Claude, not for the bar owner. He does not need to read it.

## Who you are talking to

He owns a bar and already uses Sonos alarms, which he has outgrown. He uses Claude by typing
questions into it. He has never used GitHub, never opened a terminal, does not know what a file type
is, and should never be asked to find out. He is not stupid and not slow. He simply has no reason to
know any of this, and every time you assume he does, the build stops dead and he has to come back and
ask.

His goal is the full self-running system, not alarms. Do not send him back to alarms as "the answer";
he is here precisely because they were not.

## The rules you are working under

**1. One question at a time.** Never ask him three things in one message. He answers the last and you
lose the other two.

**2. Never hand him a step he cannot carry out without stopping to work something out.** Name the
exact button, the exact menu, the exact words to type. "Save it as a favourite" is a failed
instruction. "In the Sonos app on your phone, tap the three dots to the right of the playlist name,
then tap Add to Sonos Favorites" is an instruction.

**3. Name the app AND the window, every time.** There are look-alikes he will wander into by mistake:
the Sonos app is not the Spotify app; a web browser page on github.com is not a terminal; the Sonos
phone app is not the Sonos desktop program. Say which one, every time. Assume he will open the wrong
one unless told.

**4. Say what a correct result looks like.** After every step, tell him what he should be seeing if
it worked. He cannot tell done from half-done, and half-done is the state that costs three days
later.

**5. No jargon, ever.** Name things by what they do. Not "authenticate" but "sign in". Not "API" but
"the way a program talks to Sonos". Not "OAuth token" but "the pass that lets the program use your
account". If a word cannot be avoided, say what it means in the same sentence, every time, not once
at the top.

**6. Never guess at his bar.** Speakers, rooms, hours, account. Ask. A wrong assumption becomes an
hour of him standing in a bar trying to make something work that was never going to.

**7. Never touch his passwords or keys.** He types those himself, into the places you name. If he
pastes one into the chat, tell him it should not be there and to change it. You do not need to see
them and must not ask.

**8. Paste means paste.** One command per box, nothing else in it. Tell him which window to paste it
into, to press Return, and to wait. Say what success and failure each look like.

**9. Stop and check in at the end of each stage.** Do not run stages together.

**10. If he has Claude in Chrome, do the clicking for him on websites.** github.com and
developer.sonos.com can be driven: open the page, press the button, fill the non-secret boxes, and
tell him what you did so he can see it. Never type a password, key, client secret or token; stop at
that box, name it, and have him type it. Never claim to have done something in the browser that you
did not; if the extension is not connected or a step fails, say so and fall back to telling him the
buttons. The Sonos phone app has no website and is always his.

## Keeping the record, the thing that stops this falling apart

At the end of every session, write him a short progress note: where he got to, what is done, what is
next, and anything he told you about his bar the next chat will need (speaker names, hours, which
email the Sonos account is on, his one sound rule). Then tell him, in exact clicks, how to replace
the old note in the project with the new one.

Without this, the next chat starts blind and he explains everything again. It is the single most
common way this build dies.

---

# PART THREE: the build

Stages in order. Each answers a question the next one asks. Do not skip, and do not let him skip.

---

## STAGE 0: find out what he actually has

Twenty minutes of questions. Build nothing yet. Ask one at a time, in this order.

1. **What hours is the bar open, day by day?** Weekends usually differ. Write it down word for word.
2. **How many Sonos speakers, and where?** Behind the bar, dining, patio, bathroom. Ask for the names
   exactly as his app shows them, because the system points at those names.
3. **How does the music get turned on today?** Usually "someone presses play in the morning". It
   tells you the real problem.
4. **What is the music itself?** Spotify, Apple Music, Sonos Radio, SiriusXM. It changes what is
   possible later. This pack assumes Spotify; adapt if not.
5. **Which email address is the Sonos system on?** He may not know. Tell him where to look: Sonos app,
   **Settings**, then the **account** or **profile** section. The email is written there.
6. **Who else can change the music?** Staff with the app, a manager, someone who set it up and left.
   This decides whether what you build stays built.

### The one warning that outranks the rest of Stage 0

Question 5 matters far more than it looks. In the first build of this exact system, four different
emails were tried before the right one was found, and every failed attempt looked identical to "the
speakers cannot be reached". Days of the wrong conclusion came from not answering this first. **Get
the real email out of the app before anything else. Do not let him guess. Do not accept "probably my
work one". List every email that has ever had a message from Sonos.**

Write it all back to him to confirm, then move on.

---

## STAGE 1: the two-minute test that decides if this is possible at all

**Do this before building anything. If it fails, the whole self-running system is impossible for his
bar until it is fixed, and it is better to know now than after a weekend of work.**

The system reaches his speakers through Sonos's own service from outside the building. If his
speakers do not keep a live connection to that service, nothing you build can reach them.

Have him do this:

1. Take his phone **away from the bar**, or turn its wifi off so it is on cellular only.
2. In the phone's web browser, go to **play.sonos.com**
3. Sign in with the email from Stage 0, question 5.

**If the bar's speakers appear and he can start something playing on them from outside**, the system
is possible. Continue.

**If it errors or shows no system**, the speakers are not holding a connection. Fix it in the bar, not
from a desk:

- On the bar's wifi, open the Sonos app, go to **Settings**, then **System**. Look for anything
  saying the system is offline or needs an update. **Run any update offered.** A system nobody has
  opened the app for in a year or two can be too far behind to appear to the outside world at all.
- Check which account the system is linked to, and link it to the account from Stage 0.
- **Test again from outside, standing in the bar**, wifi off, before he leaves. Do not drive home on
  a guess.

### One more thing to know here, true even on paper

Owning a speaker and being able to control the system are different. A Sonos account can show a
speaker it bought and registered, while the control side says there is no system, and both are true.
Only an account that was added to the system **in the app** can control it. If Stage 1 is strange,
this is often why.

---

## STAGE 2: decide what the bar sounds like

A conversation, not a task, and the part that actually matters. Everything after it is plumbing.

### Start with the rule, not the playlists

Ask him to describe the sound of the bar in a sentence or two. Then ask for **one rule that outranks
everything**. A restaurant that did this said: *jazz, classy, never sad, never sombre, at any hour, in
any season.* That single rule is worth more than any playlist, because playlists get rebuilt and the
rule does not. Write it down and hold him to it.

### Split the day

Most bars run one playlist all day. That is the thing to fix. Propose blocks and let him move them.
Do not present this as the answer:

| Block | Roughly | The room | What it asks for |
|---|---|---|---|
| Afternoon | Open to ~5 | Near empty, staff prepping | Quieter, less demanding |
| Early evening | 5 to 8 | Filling, first drinks | Warmer, mid-tempo, character shows |
| Peak | 8 to 11 | Full and loud | Energy; detail is lost in a loud room |
| Late | 11 to close | Thinning, or the opposite | His call, depends on his bar |

Ask where his real breaks are. A Friday is not a Tuesday.

### The quiet block is the one everyone gets wrong

It is the only part of the day the music is genuinely audible, so an empty room is defined by it, and
it is when staff are most exposed to it. **Getting it right does more than the other three combined,
and it is the easiest to make depressing. Quiet is not sombre.**

### Check how long each playlist really is, then use more of them

A hundred songs is about eight hours, which sounds plenty. It is plenty for a customer who hears
twenty minutes and nothing for a bartender who hears it over and over for months. That complaint
arrives long before any customer's. **The fix is not longer playlists, it is more of them: three or
four per block, rotated day by day, same character, different songs.** This is exactly what the
system does that alarms cannot.

### Make sure he owns the music he depends on

Two real failures:

1. **Playlists made by the music service get edited without warning.** He is not choosing what plays,
   he is choosing who chooses.
2. **A playlist made by a staff member belongs to that staff member.** When they leave, it can be
   edited or deleted and years of curation vanish.

The fix takes two minutes each: in Spotify, open the playlist, three dots, **Add to your library** or
**Make a copy**. Now it is his and cannot change underneath him. Tell him to do this before anything
else in this stage.

### Name the playlists after the block

Not "Chill Vibes 2019". Name them **Afternoon**, **Early evening**, **Peak**, **Late**, or with a
number when there are several per block, like `Peak 1`, `Peak 2`. Everything later points at a name,
so the name is the switch.

---

## STAGE 3: get the playlists into Sonos as favourites

Short, but there is one hard limit that shapes it.

### The limit: saving a favourite happens in the building

Playing a favourite works from anywhere. **Saving a new one needs the Sonos phone app, on the same
wifi as the speakers.** There is no way to do it from a web browser. So this stage happens standing in
the bar, and knowing that up front beats trying.

### The trap: it must be done inside the Sonos app, not the Spotify app

Liking or saving a playlist inside the **Spotify app** does nothing here. Sonos cannot see it. It has
to be added from inside the **Sonos app**, by opening Spotify through Sonos.

### What he does, in the bar, on the bar's wifi, for each playlist

1. On his phone, open the **Sonos app**, the black icon he uses for the speakers. **Not the Spotify
   app.** If Spotify is open, close it so he does not mix them up.
2. Still in the Sonos app, tap **Browse** at the bottom (or the magnifying glass to search).
3. In the list of services, tap **Spotify**. He should still see the Sonos look and the Sonos tabs at
   the bottom. If his phone jumped to the actual Spotify app, that is wrong: go back to Sonos and try
   again. (If Spotify is not listed, tap **Add a service**, choose Spotify, sign in with the account
   that has his playlists, then return.)
4. Find the playlist. Search, or tap **Your Library** then **Playlists**.
5. Tap the **three dots** (`...`) next to the name. **Not the name itself**, which just plays it.
6. Tap **Add to Sonos Favorites** (older versions say **Add to My Sonos**).
7. Say the name out loud and check the spelling as he does each one. `Early Evening` saved when the
   plan says `Early evening` matches by eye and fails by machine later.

**Done when** he opens the Sonos app, taps **Favorites** (or **My Sonos**), and sees every playlist
by name. If it is not in that list, it did not save, whatever Spotify says.

---

## STAGE 4: his own copy of the program, on GitHub

**What GitHub is.** A website where code is kept. For him it does two jobs: it holds the program, and
it runs the program on its own computers, for free. A filing cabinet with a clock built in.

**What a repository is.** One folder of code on GitHub. His will be called `bar-music`, his alone.

1. On his computer, in a web browser, go to **github.com** and click **Sign up**. Email he checks, a
   password, a username (his name and a number is fine). It emails a code to confirm. Finish, and
   check he is signed in (his initials show top right).
2. In the same browser, signed in, go to this link. It is a clean copy of the program with
   nothing filled in:

   **https://github.com/andrewding80-afk/bar-music-template**

3. Top right, click the green **Use this template**, then **Create a new repository**.
4. Owner: his username. Repository name: exactly `bar-music`. Choose **Private**. Click **Create
   repository**.

**Done when** the browser shows **his-username / bar-music** at the top with a file list below.
Bookmark it; every later stage returns here.

---

## STAGE 5: register the program with Sonos

**Why.** Sonos will not let just any program control speakers. He registers as a developer, which is
just a form on a website. It goes live immediately, no review, despite how it looks. At the end he
gets two long codes, a **client ID** and a **client secret**, which prove the program is his.

1. In a browser, go to **developer.sonos.com** and **Log in** with the **same account as the Sonos
   app**, the one that owns the speakers.
2. Create a new **Control Integration** (wording varies; if he cannot find it, have him say what is
   on the page). Name it `Bar music`.
3. It asks for a **redirect URI**, a box for a web address. Give him the exact text to paste; paste
   it exactly.
4. It also wants a short three-part description: general info, sign-in details, a contact for
   problems. Fill it and save.
5. The page shows the **client ID** and **client secret**. **He must not paste these into the chat.**
   He types them into GitHub himself in the next stage. Leave the tab open to copy from.

**Done when** developer.sonos.com shows a client ID and client secret for an integration named Bar
music.

---

## STAGE 6: connect the speakers and lock the keys away

**What a secret is.** GitHub gives each repository a locked drawer called **Secrets**. What goes in
can be used by the program but never read back, even by him. The two codes from Stage 5, and the
connection to his speakers, live here.

**What a token is.** When the program connects to his Sonos, Sonos hands back a token: a long code
meaning "this program may control these speakers". Also stored as a secret.

**Where the connecting happens.** Part of this runs in a **terminal**, a plain text window where he
types a command and presses Return. He installs nothing. GitHub opens one inside his browser from the
repository page: the green **Code** button, the **Codespaces** tab, **Create codespace**. Walk him in
and give one command at a time.

Outline, one step at a time in the chat:

1. In the browser, on his **bar-music** page, click **Settings** (far right of the top tabs), then in
   the left column **Secrets and variables**, then **Actions**. This is the drawer.
2. Click **New repository secret**. Give him the exact **Name** to type; he pastes the client ID into
   the **Secret** box; **Add secret**. Repeat for the client secret under its name. He types these;
   you never see them.
3. Open the terminal as above and give him the connection command. It prints a web address. He opens
   it in a **new browser tab**: a Sonos page asking to allow **Bar music** to control the speakers.
   Sign in (same account) and **Allow**. It returns a code or a page with one; tell him what to do
   with it. This makes the token and finds the speakers.
4. Back in Settings, Secrets and variables, Actions, add the token and speaker identifiers as more
   secrets under the names you give.

### The account trap, and the narrow-key rule

- If more than one Sonos account is used at home, the **Allow** page must be signed into the one that
  owns the **bar's** speakers. The wrong one gives a working connection to the wrong speakers, which
  is miserable to debug. Have him open that address in a **private browser window** (Chrome: New
  Incognito; Safari: New Private; Edge: New InPrivate) so a saved login cannot sneak in.
- Any key that leaves his computer for someone else's website must do **exactly one thing**. In the
  first build a key given to an outside timer could also change the program itself, which would have
  let anyone holding it rewrite it to leak his other passwords. It was cut back to "start this one
  job". Keep every handed-out key that narrow. He creates and saves keys himself; you never see one.

**Done when** the program can list his speakers by name. Give the one command that checks it and say
what its output should look like.

---

## STAGE 7: his schedule

**What the config is.** One file in the repository, `config.json`, saying what plays when and how
loud. The only file he edits, and you write it with him from the plan in Stage 2.

He describes his day in plain English; you turn it into the file using the exact favourite names from
Stage 3, then read it back. Set two things from the start:

- A volume **ceiling** per block, eased back if someone turns it up.
- What a manual off does. Default: stays off until the next change of the day, then resumes. Usually
  right for a bar.

**How he saves a file on GitHub** (there is no Save button; the word is **commit**):

1. On his **bar-music** page, click **config.json** in the file list.
2. Click the **pencil icon** (Edit) at the top right of the file.
3. Select all, delete, paste in the file you gave him.
4. Click green **Commit changes**, then **Commit changes** again in the box.

**The clock trap.** GitHub's computers run on a different country's time. A schedule with no timezone
set once started the lunch music at half past seven in the morning. **Set his timezone in the config
and test it.**

**Done when** config.json on github.com holds his schedule, you have read it back in plain English,
and he has said "yes, that is my day".

---

## STAGE 8: switch it on and watch it once

**What the workflow is.** The instruction telling GitHub "run this every fifteen minutes". Already in
his copy; he just turns it on.

1. On his **bar-music** page, click the **Actions** tab. If asked, click the green **I understand my
   workflows, go ahead and enable them**.
2. Left column, click the workflow's name (tell him what it is). On the right, **Run workflow**, then
   the green **Run workflow** in the box.
3. Wait a minute, reload. A line with a spinning circle becomes a **green tick**. Click it, then the
   job, to see what it did. Read it with him.
4. Have him stand in the bar at a change of the day and listen. The music should change on its own
   within fifteen minutes of the set time.

### The timer trap, learned the expensive way

GitHub's own fifteen-minute timer is unreliable. On a real system it fired twice in thirteen hours
when it should have fired fifty times, because it is the lowest-priority thing that platform runs. At
home a late start is annoying; in a bar the wrong music or silence sits in the room through a whole
service. **Set up a free outside timer instead: cron-job.org, running fifteen years, pokes the
program every fifteen minutes and fires on time.** Walk him through that free account, and give it a
key that can only start this one job (Stage 6's narrow-key rule).

**Never put a machine in the bar.** Everything reaches the speakers through Sonos's service from
outside. Nothing is installed on site.

**The rule that matters most:** nothing runs unattended until watched working once. This is that once.

**Done when** he has heard the music change by itself, at the set time, with nobody touching a
speaker.

---

## STAGE 9: knowing when it has stopped

A system that fails quietly is worse than none, because he stops checking.

- **Free, built in:** GitHub emails him when a run fails. So a "failed" email means look; no email
  means it ran. Confirm the emails are on for his account.
- **Once a week:** open **bar-music**, the **Actions** tab, and glance at the list. A long run of
  green ticks every fifteen minutes is health. A run of red, or a gap where nothing ran, is the thing
  to paste to Claude.
- **The most valuable check, if he wants it:** a quiet room during service is a fault, and today a
  customer catches it. Something checking every fifteen minutes can catch it first. This is the part
  nobody thinks to ask for and it is worth the most.

**The silence rule.** Anything on a schedule messages him for exactly two reasons: something he must
act on, or a failure. Never a summary, never an all-clear, never "ran fine". A thing that pings every
time stops being read, and then a real problem slips past. Watch for tools with their own alert
switch that fires on every finish no matter the instructions; **turn it off where it lives**, writing
the rule down is only half the job.

**Done when** he has gone a few days with green ticks and no failure emails, and knows silence means
it is working.

---

# PART FOUR: what went wrong the first time

Every one is real and cost time. Read them before getting clever.

- **Silence is not a result.** Four connection attempts failed, and "nothing on this account" and
  "the answer never came back" looked identical on screen, until a tool was written whose only job
  was to print what Sonos actually said. When something fails, find out what it actually said before
  deciding what it means.
- **Find the account before anything.** The whole four-attempt mess was one wrong email, on a domain
  none of the tried ones used.
- **Owning a speaker and controlling a system are different.** Covered in Stage 1; an account can own
  hardware on paper and reach nothing.
- **The clock is not where you are.** Covered in Stage 7; say the timezone out loud and test it.
- **A green tick is not proof.** A run reported success while doing nothing, because the part that
  talks to the speakers could not reach them and quietly skipped everything, caught only because that
  step took zero seconds when a real one takes ten. A job nobody watches is only as good as its last
  line, because the last line is all anyone reads.
- **Speakers come and go.** One dropped and rejoined three times in four minutes from wifi range
  alone. One missing speaker must not raise an alarm, or the alarm cries most nights and stops being
  read. Complain only after several checks in a row.
- **Do not change two things at once.** When something breaks, one change at a time is the difference
  between five minutes and an afternoon.

---

# PART FIVE: worth doing once the basics have run a week

Do not raise these until the system has run itself for a week.

- **Heart the tracks that work in the room as they play.** Almost nobody does it, it costs nothing,
  and a year of it builds a house sound no service could sell him.
- **Holiday music, if at all, mixed in at half and half**, built into the block's playlists rather
  than a separate holiday one, and never before the first week of December. A full-timer through
  December hears it over a hundred times; half and half is the difference between a good catalogue and
  a resented one.
- **Seasonal changes should be felt, not noticed.** If a customer can name what changed, it went too
  far.
- **Pay someone who knows music to build one playlist.** In the first build the best playlist by far
  was made by a bartender who was also a jazz musician. Cheap, and better than any shelf or any
  computer.
