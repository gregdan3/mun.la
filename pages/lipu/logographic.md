% Could [sitelen+pona]{.tp} stop being logographic?
% gregdan3
% 2025-02-27
% published: false

### tl;dr

No. [sitelen+pona]{.tp} is not practical for much more phonetic writing than it
currently does in cartouches, mostly because of [toki+pona]{.tp}'s vocabulary
limiting it in the first place. Even if you tried, any phonetic
[sitelen+pona]{.tp} would either be the logographic system again or be worse
than it, and _good luck_ if you want to adapt [sitelen+pona]{.tp} to another
language. You _can_ make a phonetic system out of [sitelen+pona]{.tp}, but it
won't see adoption.

### Preamble

Near the end of January, the Unicode Consortium got back to us about
[our proposal to encode [sitelen+pona]{.tp} in Unicode](https://www.unicode.org/L2/L2024/24275-encode-sitelen-pona.pdf).
You can
[see their comments here](https://www.unicode.org/L2/L2025/25010-script-wg-report.pdf#page=10)
in section 6.6 of their Q1-2025 meeting minutes. They did not have much to say,
because our proposal is preliminary and thus not requesting any action to be
taken at this time. However, they did provide some useful comments about our
proposal, which will become important when we submit our finalized proposal.

But one of their comments was deeply confusing.

Per the following quote, the Unicode Consortium is concerned that
[sitelen+pona]{.tp} may not be logographic. That is, they believe
[sitelen+pona]{.tp} symbols may be or become used for their phonetic value
(sound) rather than their semantic value (meaning).

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
believe that [sitelen+pona]{.tp} is either not logographic, or that it may no
longer be logographic at some point in the future.

But we're missing the "why." We intend to reach out for further comment in the
future, but right now we're waiting on that. In the meantime, let's investigate
the issue ourselves: How does a logographic writing system become phonetic? How
long does it take? Could it happen to [sitelen+pona]{.tp}?

---

### How does a logographic writing system become phonetic?

I can't give a complete answer as to how a logographic writing system becomes
phonetic, as I am not a linguist or other language-history expert. However, I
can walk you through at least one demonstrative example:

Japanese's two phonetic syllabaries,
[Hiragana](https://en.wikipedia.org/wiki/Hiragana) and
[Katakana](https://en.wikipedia.org/wiki/Katakana), both developed as a
simplification of a prior system called
[Man'yōgana](https://en.wikipedia.org/wiki/Man%27y%C5%8Dgana), which was itself
an adaptation of [Hanzi](https://en.wikipedia.org/wiki/Chinese_characters).
However, unlike the many
[Sinitic languages](https://en.wikipedia.org/wiki/Sinitic_languages) that
primarily used these symbols for their meaning, Man'yōgana primarily used Hanzi
characters for their sound in order to write Japanese. Specifically, the full
sound of a Hanzi character would be used to represent some number of syllables
in Japanese.

Linguists call this the
[rebus principle](https://en.wikipedia.org/wiki/Rebus#Rebus_principle), where a
symbol is used for its sound rather than its meaning in order to write a word.
This practice can be used to write names, such as the example of Ramesses II
given in the linked article, but it can be used to write essentially anything-
and it often occurs when adapting a language's logographic writing system to
another language. This is exactly how Man'yōgana arose.

That said, a writing system does not have to be adapted to a different language
for the rebus principle to be used- it can occur within the same language so
long as a given symbol has a sound that can be reused within that language. This
can even be done in English via emoji, where the eye emoji `👁️` can be read for
its sound and not what it depicts, thus representing the first person pronoun
"I."

I'll also note for completeness that a symbol does not have to be used for its
entire sound (as in the rebus principle) to be used phonetically. It is possible
to use only the first consonant or vowel,
[mora](<https://en.wikipedia.org/wiki/Mora_(linguistics)>), syllable, or another
partial or modified reading of the character. That said- and this is a _lightly
educated guess_, not fact- I'd assume that most of these were rare and widely
unconsidered before the studies of phonetics and linguistics were widespread.

This is important to clarify though, because [sitelen+pona]{.tp} as defined in
_Toki Pona: The Language of Good_ already has one of these systems available,
where symbols in a cartouche are read by their first letter. Further, there are
other community-made systems for writing names which are based on morae instead.

---

<!--I believe [sitelen pona]{.tp} will remain a logographic script.-->

But does [sitelen+pona]{.tp} even make a good phonetic script? Personally, I
don't think so. My hypothesis is that cartouches will remain the only means by
which [sitelen+pona]{.tp} is written phonetically, while the majority of
[sitelen+pona]{.tp} writing will remain logographic. Here's my argument for why:

### Phonetic [sitelen+pona]{.tp} is only good at writing [toki+pona]{.tp}

<!--Writing-->
<!--phonetically in [sitelen pona]{.tp} is too inconvenient for uses that go much beyond-->
<!--the scope of names-->

<!-- 1. phonetic sitelen pona is severely limited by toki pona's own vocabulary, so -->
<!--    there are many sounds you cannot portray even within the extreme limitations -->
<!--    of toki pona -->
<!-- 2. phonetic sitelen pona is difficult to portray without cartouches, so adding -->
<!--    phonetic systems to the written language is difficult or impossible -->
<!-- 3. everyone knows the latin alphabet anyway, and it's way better -->
<!-- 4. sitelen pona sucks bad for writing toki pona phonetically, but it would suck -->
<!--    so much worse for writing almost any other language -->

[sitelen+pona]{.tp}'s existing phonetic system and the community-made extensions
to it are extremely limited in what sounds they are able to express. However,
these limits do not come from the systems themselves. In fact, these community
extensions are generally created to _add to_ the capabilities of the cartouche
system from _Toki Pona: The Language of Good_. These additions often make names
more compact by writing morae rather than letters, and offer more variety of
symbols for writing names.

However, these changes do not escape the biggest limitation of phonetic writing
in [sitelen+pona]{.tp}, which is [toki+pona]{.tp}'s own vocabulary. An extreme
example of this issue can be seen in the options available to write "e" in the
initial-letter-based system defined in _Toki Pona: The Language of Good_,
because the only options are [e]{.tp}, [en]{.tp}, and [esun]{.tp}. (Anecdotally,
those trying to write their own name are routinely frustrated by the limited
ways to write "e"). Generalizing this, [toki+pona]{.tp} does not equally
distribute the letters of its latin alphabet across its words, and phonetic
[sitelen+pona]{.tp} inherits this trait.

<!--Anecdotally, most people dislike how sincerely boring these options are compared-->
<!--to the wide variety of options for writing "k" or "s" or other letters-->

<!--Even the various improved phonetic systems are unable to get around-->
<!--[toki+pona]{.tp}'s limited vocabulary and the distribution of its sounds.-->

To demonstrate: While these systems offer more ways to write "e" _if_ it comes
after a consonant, morae like "pe", "ju", and "nu" are unavailable without
falling back on the less effective letter-based system, and several morae like
"pu" or "je" have only a single option available, or are only available after
other sounds. (And again, this is a routine point of frustration for those
writing their own names).

<!--and this is the primary motivation to create better phonetic writing-->
<!--systems out of [sitelen+pona]{.tp}.-->

Summarizing the above, phonetic [sitelen+pona]{.tp} is only particularly good at
writing words which are already in [toki+pona]{.tp} because the needed sounds
are already available in the desired order via [toki+pona]{.tp}'s vocabulary.
Name writing is not _much_ more challenging than that, but a variety of sounds
which [toki+pona]{.tp}'s phonotactics allow are not possible to represent as
more compact morae, and so must be written while treating [sitelen+pona]{.tp} as
a poor alphabet.

Based on the above, not only is [sitelen+pona]{.tp} only _okay_ at writing names
that follow [toki+pona]{.tp}'s phonotactics,' it would be _extremely bad_ at
writing languages other than [toki+pona]{.tp} unless its sounds were
significantly altered for that purpose. There are extremely few other languages
with as few sounds to represent, and as demonstrated, phonetic
[sitelen+pona]{.tp} has significant limits even for writing sounds that are
allowed in [toki+pona]{.tp}.

### Phonetic [sitelen+pona]{.tp} is worse than logographic [sitelen+pona]{.tp}

Phonetic [sitelen+pona]{.tp} is a much less efficient format for conveying
[toki+pona]{.tp} than logographic [sitelen+pona]{.tp}. I touched on this briefly
in the prior section while discussing compactness of the various name writing
systems, but the issue is much larger than I portrayed then. The loss in
efficiency of any phonetic system versus the logographic one can be demonstrated
visually with ease. Compare these options for writing the sound "toki", ordered
from least to most compact:

| System          | Writing                                                    |
| --------------- | ---------------------------------------------------------- |
| Alphabetic      | [[taso olin kasi ike]]{.tp} or [[tawa ona kala insa]]{.tp} |
| Moraic          | [[tomo. kili.]]{.tp} or [[tonsi. kin.]]{.tp}               |
| Unmarked moraic | [[tomo kili]]{.tp} or [[tonsi kin]]{.tp}                   |
| Rebus           | [[toki:]]{.tp}                                             |
| Unmarked rebus  | [[toki]]{.tp}                                              |
| Logographic     | [toki]{.tp}                                                |

As you can see, each of these markings become progressively smaller until they
ultimately represent the word again. Even if you ignore the cartouches, the only
phonetic systems which can compare to the efficiency of logographic
[sitelen+pona]{.tp} are essentially identical to writing logographically.

The problem of compactness only becomes worse for longer words and names where
the efficiency of writing the word drops even further, and this doesn't even
consider the massively expanded number of ways to write any given word. Even if
you assume that users of phonetic [sitelen+pona]{.tp} will settle on a single
way to write each sound or at least each word[^agreement], all words would have
a significantly longer representation in the phonetic writing system than the
logographic system, but not gain any new expressive power over the Latin
alphabet.

[^agreement]:
    So we're clear, this assumption is _lofty._ Even for the fact that
    [toki+pona]{.tp} only has a few thousand speakers at most.

Now, I'll grant that "It should be logographic! Look how short it is to write!"
is a bad argument _on its own_. Compactness is not the only consideration in a
writing system; after all, making a logography for English would be absurd,
because it has hundreds of thousands of words, and even
[simplified versions of it](TODO) still have over a thousand words. However,
[toki+pona]{.tp}'s vocabulary of only 120-130 words requires only that many
logographs to fully represent it- that many symbols needed to read and write the
language.

This means the efficiency advantage of an alphabet or syllabary over a
logography is much smaller for [toki+pona]{.tp} than any natural language. Let's
examine the math of it.

For an alphabetic writing system, you would only need 14 symbols to represent
[toki+pona]{.tp}: One for each letter [toki+pona]{.tp} uses. [sitelen+pona]{.tp}
has over 100 "letters", and agreeing on which to use for what letter would
likely take decades if it could ever be achieved.

For a moraic writing system, you would need around 50 symbols, but
[sitelen+pona]{.tp} can't represent them all based on the initial mora of
[toki+pona]{.tp}'s words- you'd need to create new rules/readings to make up the
difference, or just write some words logographically anyway. Even then, you
would still need to know about half as many symbols as there are words in the
language, which makes for an even smaller gap between it and a logography.

It's also worth reiterating that all of these flaws of phonetic
[sitelen+pona]{.tp} affect its ability to write _any language_, not just
[toki+pona]{.tp}

To summarize, _an_ alphabet would be more efficient than logographic
[sitelen+pona]{.tp}. It already exists, and is called the Latin alphabetic. But
[sitelen+pona]{.tp} does not make a good alphabet, and the rest of the phonetic
systems for [sitelen+pona]{.tp} are worse than it.

<!--Even for writing [toki+pona]{.tp}, phonetic [sitelen+pona]{.tp} would be less-->
<!--compact and less consistent to read due to the variety of ways many important-->
<!--sounds can be written. In other words, logographic [sitelen+pona]{.tp} is always-->
<!--going to be a more efficient writing system for [toki+pona]{.tp} than any-->
<!--phonetic system made using [sitelen+pona]{.tp}.-->

<!--Now, I do need to note that alphabets and syllabaries are _generally_ more-->
<!--efficient than logographies- but the reason for this is the number of distinct-->
<!--symbols that must exist in order to portray the language.-->

### Every [toki+pona]{.tp} speaker already knows the Latin alphabet

and like, let's not forget that virtually if not literally every speaker of toki
pona already knows the latin alphabet, which is inextricably and likely
permanently toki pona's primary writing system- and it's objectively more useful
than any phonetic system sitelen pona could convey, including its own built in
one, even if you artificially limit it to toki pona's phonotactics. there's a
huge pressure to just use the latin alphabet rather than make up a new system
that you'd have to push everyone to learn first.

### Mixing phonetic and logographic [sitelen+pona]{.tp} cannot work

It also bears mentioning that [toki pona]{.tp}'s highly limited grammar prevents
virtually any phonetic system from omitting cartouches unless it wholly replaced
the existing logographic system. Without a cartouche, phonetic writing with [sitelen
pona]{.tp}
blurs into the surrounding sentence, making it nearly impossible to separate .
I'll grant, somebody could make a totally new system or marking that could
better distinguish between symbols used for their sound and symbols used for
their meaning. But even if that tool were created, or if [sitelen+pona]{.tp}
were written entirely phonetically in some idealized system, it would still only
be [sitelen+pona]{.tp} would only be capable of writing

this one can't be discounted, but even an idealized phonetic system made with
sitelen pona is still not gonna be very good at writing anything except for toki
pona... in which case, why would anyone bother?

<!--You'll note that up to this point, I've focused on how [toki+pona]{.tp} could be-->
<!--written using phonetic [sitelen+pona]{.tp}, but I haven't mentioned-->

so, that's my argument for why non-logographic sitelen pona won't happen.
summarizing: phonetic writing systems made with sitelen pona will only really be
good at writing toki pona, but they'd probably be worse than sitelen pona _and_
have to be taught. and otherwise, the latin alphabet is right there, and way
better at this job.

---

By the way, if you take this article as a challenge to create a better phonetic
system out of [sitelen+pona]{.tp}, whether to write [toki+pona]{.tp} or other
languages, [please do so and share](TODO)! I'd love to see what you come up
with. But be aware, you can't just tack new sounds onto these symbols- whatever
system you create needs to be reasonably familiar to existing speakers, and easy
to explain!
