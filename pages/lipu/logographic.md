% Could [sitelen+pona]{.tp} stop being logographic?
% gregdan3
% 2025-02-15
% published: false

Near the end of January, the Unicode Consortium got back to us about
[our efforts to encode [sitelen+pona]{.tp}](https://www.unicode.org/L2/L2024/24275-encode-sitelen-pona.pdf)
in Unicode. You can
[see their comments here](https://www.unicode.org/L2/L2025/25010-script-wg-report.pdf#page=10)
in section 6.6 of their Q1-2025 meeting minutes. They did not have much to say,
because our proposal is preliminary and thus not requesting any action to be
taken at this time. However, they did provide some useful comments about our
proposal, which will become important when we submit our finalized proposal.

But one of their comments was deeply confusing.

Per the following quote, the Unicode Consortium is concerned that sitelen pona
may not be logographic. That is, they believe sitelen pona symbols may be or
become used for their phonetic value (sound) rather than their semantic value
(meaning).

> ... there is no indication ... **that [the script] is logographic in nature** (which
> would make it constrained to the language).

When we read this, we had no idea where their concern was coming from. We
reached out via email to clarify this statement among others, and Jan Kučera
replied with the following:

> As an opened-ended [sic] system, and with examples as above, some members were
> not convinced the script indeed is or will remain logographic in the future,
> ...

Restating this, our understanding of Unicode's initially stated concern is
correct: some members of
[Unicode's Script Encoding Working Group](https://www.unicode.org/consortium/scriptadhoc.html)
believe that [sitelen pona]{.tp} is either not logographic, or that it may no longer
be logographic at some point in the future.

But we're missing the "why." We intend to reach out for further comment in the
future, but right now we're waiting on that. In the meantime, let's investigate
the issue ourselves: How does a logographic writing system become phonetic? How
long does it take? Could it happen to [sitelen+pona]{.tp}?

---

I can't give a complete answer as to how a logographic writing system becomes
phonetic, as I am not a linguist or other language-history expert. However, I
can give at least one demonstrative example:

Japanese's two phonetic syllabaries,
[Hiragana](https://en.wikipedia.org/wiki/Hiragana) and
[Katakana](https://en.wikipedia.org/wiki/Katakana), both developed as a
simplification of a prior system called
[Man'yōgana](https://en.wikipedia.org/wiki/Man%27y%C5%8Dgana), which was itself
an adaptation of [Hanzi](https://en.wikipedia.org/wiki/Chinese_characters).
However, unlike the many
[Sinitic languages](https://en.wikipedia.org/wiki/Sinitic_languages) that
primarily used these symbols for their meaning, Man'yōgana primarily used Hanzi
characters for their sound in order to write Japanese. Specifically, the sound
of a Hanzi character would be used to represent some number of syllables in
Japanese.

Linguists call this practice the
[rebus principle](https://en.wikipedia.org/wiki/Rebus#Rebus_principle), where a
symbol is used for its sound rather than its meaning. This practice can be used
to write names, such as the example of Ramesses II given in the linked article,
but it can be used to write essentially anything- and it often occurs when
adapting a one language's logographic writing system to another language. This
is exactly how Man'yōgana arose.

That said, the rebus principle does not have to be used to write a different
language- it can take place within the same language so long as a given symbol
has a sound that can be reused within that language. This can even be done in
English via emoji, where the eye emoji `👁️` can be read for its sound and not
what it depicts, thus representing the first person pronoun "I."

I'll also note for completeness that a symbol does not have to be used for its
entire sound (as in the rebus principle) to be used phonetically. It is possible
to use only the first consonant or vowel,
[mora](<https://en.wikipedia.org/wiki/Mora_(linguistics)>), syllable, or another
partial or modified reading of the character. That said- and this is a _lightly
educated guess_, not fact- I'd assume that most of these were rare and widely
unconsidered before the study of phonetics was widespread.

This is important to clarify though, because [sitelen+pona]{.tp} as defined in
Toki Pona: The Language of Good already has one of these systems available,
where symbols in a cartouche are read by their first letter. Further, there are
other community-made systems for writing names which are based on morae instead.

---

<!--I believe [sitelen pona]{.tp} will remain a logographic script.-->

But does [sitelen+pona]{.tp} even make a good phonetic script? Personally, I
don't think so. My hypothesis is that cartouches will remain a permanent release
valve for any potential adaptation of sitelen pona to phonetic writing. Here's
my argument for why:

<!--Writing-->
<!--phonetically in [sitelen pona]{.tp} is too inconvenient for uses that go much beyond-->
<!--the scope of names-->

[sitelen pona]{.tp}'s existing phonetic system and the community-made extensions
made to it are extremely limited, in ways that come primarily from [toki+pona]{.tp}'s
own vocabulary. As a clear example of this, you have exactly three ways to write
"e" in the system from Toki Pona: The Language of Good- [e]{.tp}, [en]{.tp}, and
[esun]{.tp}- and anecdotally, most people don't like using any of them. Then, even
if you expand this to include the various moraic naming systems, morae like "pe",
"ju", and "nu" are unavailable, and some only have exactly one option like "pu."

If that were not enough of a problem, [toki pona]{.tp}'s highly limited grammar prevents
virtually any phonetic system from omitting cartouches. Without a cartouche, phonetic
writing with [sitelen pona]{.tp} blurs into the rest of the sentence, turning it
into visual mush. I'll grant, somebody could make a totally new tool that could to distinguish between symbols used for their sound and
symbols used for their meaning. But even if that tool were created, or if
[sitelen+pona]{.tp} were written entirely phonetically in some idealized system,
it would still only be [sitelen+pona]{.tp} would only be capable of writing

this one can't be discounted, but even an idealized phonetic system made with
sitelen pona is still not gonna be very good at writing anything except for toki
pona... in which case, why would anyone bother?

and like, let's not forget that virtually if not literally every speaker of toki
pona already knows the latin alphabet, which is inextricably and likely
permanently toki pona's primary writing system- and it's objectively more useful
than any phonetic system sitelen pona could convey, including its own built in
one, even if you artificially limit it to toki pona's phonotactics. there's a
huge pressure to just use the latin alphabet rather than make up a new system
that you'd have to push everyone to learn first.

so, that's my argument for why non-logographic sitelen pona won't happen.
summarizing: phonetic writing systems made with sitelen pona will only really be
good at writing toki pona, but they'd probably be worse than sitelen pona _and_
have to be taught. and otherwise, the latin alphabet is right there, and way
better at this job.
