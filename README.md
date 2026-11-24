[![make.fun · u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/giandisruw/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/rank.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/giandisruw/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/reward.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

# Ridiculous at First Glance, Real by the Second

Entry for the make.fun bounty [Ridiculous at First Glance, Real by the Second](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a) — one sentence, at most 200 characters, pitching a bizarre startup idea that sounds absurd until you realise it would actually sell.

## The line

**We sell naming rights to potholes: drivers pay $5 to name the crater that ate their tyre, and the council fills the named ones first because nobody wants to hit 'Dave's Revenge' twice.**

Character count: **184** (limit: 200).

## How it works

`main.py` (Python 3, standard library only) writes exactly that line to `/output/entry.txt` — no trailing newline, nothing else. Before writing, it validates the line: 1–200 characters, a single line, no leading or trailing whitespace, no control characters. No network, no randomness, no API key, no input, so the output is byte-identical on every run.

```bash
python3 main.py
```

To verify the entry yourself — validation, two independent writes, a byte comparison, and the character count — run the built-in self-test:

```bash
python3 main.py --self-test
```

It prints the line, its character count, a PASS/FAIL verdict for each check, and exits 0 only if every check passes. It writes only to a fresh temporary directory and leaves `/output/entry.txt` untouched.

## Why it holds together

The absurdity is immediate — who would pay to name a hole in the road? — and the second look is where it becomes a real business. Drivers pay $5 for the catharsis of naming the crater that ate their tyre, and the council fills the named ones first, because a crater with a public name and a queue of angry drivers behind it is a repair job nobody wants to keep postponing. The buyer (drivers), the price ($5), and the mechanism (public naming creates pressure to fix) are all in the sentence, and the punchline — nobody wants to hit "Dave's Revenge" twice — is the turn from laughing to nodding.

## Choosing the line

Eight candidates were drafted and ranked in a single-elimination pairwise tournament judged by the local Caffeine router against the bounty's own published criteria (genuinely bizarre, business logic holds, laugh-to-nod turn, concrete buyer and thing). The pothole line won its quarter-final against the rent-a-goat pitch, its semi-final against the grocery-carry gym, and the final against the festival dog-toilet pitch in both orders.

1. **"We sell naming rights to potholes: drivers pay $5 to name the crater that ate their tyre, and the council fills the named ones first because nobody wants to hit 'Dave's Revenge' twice."** — 184 chars. **Winner.** A genuinely novel idea (not a familiar business with a strange adjective), clear payer and price, and the payment logic is the joke itself.
2. **"We rent driveways near music festivals as pop-up dog toilets: homeowners earn $40 a day, and 10,000 desperate festival-goers will pay anything for a legal patch of grass."** — 170 chars. Runner-up. Vivid and the festival economics are concrete, but the premise leans on a one-weekend-a-year market.
3. **"We bottle the air of your childhood hometown and sell it to homesick expats for $29 a jar, because one sniff of rainy Tuesday beats a therapy session and ships cheaper than a flight."** — 182 chars. Strong emotional logic, but bottled air as a novelty gift is a familiar gag rather than a new idea.
4. **"A gym where the only workout is carrying strangers' groceries up five flights of stairs: flat-dwellers pay $15 a session, because their shopping arrives and their legs get the workout."** — 184 chars. Funny dual payoff, but the buyer is doing the paying and the working at once, which muddies who the customer is.
5. **"We hire professional mourners to weep at strangers' funerals: grieving families pay $200 a head, because a packed, tearful send-off is the last thing anyone should fake alone."** — 175 chars. Clear payer and price, but professional mourning is a real, known practice in several cultures, so it scores lower on novelty.
6. **"A dating app that matches you only with people who hate the same things you do: singles pay $7 a month, because bonding over a shared enemy beats small talk and the first date is a complaint."** — 191 chars. Good turn, but "hate the same things" is a familiar dating-app twist.
7. **"We sell apology letters written by your dog: guilty owners pay $12 a pop, because the vet bill stings less when the culprit says sorry in paw print."** — 148 chars. Charming, but the market (one guilty purchase per chewed shoe) is thin.
8. **"We rent out hungry goats to mow suburban lawns: homeowners pay $49 a visit, because the goats eat the weeds, fertilise as they go, and the neighbours' kids think it's a petting zoo."** — 181 chars. Rent-a-goat is a real, established business, so it fails the "never heard before" test outright.

The first draft of the winner was shorter and flatter — "We sell naming rights to potholes: drivers pay $5 to name the crater that wrecked their tyre, and the council fixes the named ones first." (152 chars) — and the revision added "ate their tyre", "fills", and the named pothole "Dave's Revenge", which is where the laugh-to-nod turn actually lives. See the revision note in `main.py`.

Referral code: 0txwmf1m

## License

MIT — see [LICENSE](LICENSE).
