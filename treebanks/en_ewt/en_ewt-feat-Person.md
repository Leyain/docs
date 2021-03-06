---
layout: base
title:  'Statistics of Person in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Features: `Person`

This feature is universal.
It occurs with 3 different values: `1`, `2`, `3`.

26229 tokens (10%) have a non-empty value of `Person`.
558 types (3%) occur at least once with a non-empty value of `Person`.
452 lemmas (3%) occur at least once with a non-empty value of `Person`.
The feature is used with 3 part-of-speech tags: <tt><a href="en_ewt-pos-PRON.html">PRON</a></tt> (18681; 7% instances), <tt><a href="en_ewt-pos-AUX.html">AUX</a></tt> (5235; 2% instances), <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> (2313; 1% instances).

### `PRON`

18681 <tt><a href="en_ewt-pos-PRON.html">PRON</a></tt> tokens (81% of all `PRON` tokens) have a non-empty value of `Person`.

The most frequent other feature values with which `PRON` and `Person` co-occurred: <tt><a href="en_ewt-feat-PronType.html">PronType</a></tt><tt>=Prs</tt> (18681; 100%), <tt><a href="en_ewt-feat-Poss.html">Poss</a></tt><tt>=EMPTY</tt> (15021; 80%), <tt><a href="en_ewt-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (13863; 74%), <tt><a href="en_ewt-feat-Case.html">Case</a></tt><tt>=Nom</tt> (11781; 63%), <tt><a href="en_ewt-feat-Number.html">Number</a></tt><tt>=Sing</tt> (11046; 59%).

`PRON` tokens may have the following values of `Person`:

* `1` (7964; 43% of non-empty `Person`): <em>i, my, we, me, our, us, myself, 's, ourselves, s</em>
* `2` (3620; 19% of non-empty `Person`): <em>you, your, yourself, u, ur, yourselves</em>
* `3` (7097; 38% of non-empty `Person`): <em>it, they, he, their, his, them, him, she, her, its</em>
* `EMPTY` (4280): <em>that, this, what, there, who, which, anyone, something, anything, nothing</em>

`Person` seems to be **lexical feature** of `PRON`. 100% lemmas (23) occur only with one value of `Person`.

### `AUX`

5235 <tt><a href="en_ewt-pos-AUX.html">AUX</a></tt> tokens (34% of all `AUX` tokens) have a non-empty value of `Person`.

The most frequent other feature values with which `AUX` and `Person` co-occurred: <tt><a href="en_ewt-feat-Mood.html">Mood</a></tt><tt>=Ind</tt> (5235; 100%), <tt><a href="en_ewt-feat-Number.html">Number</a></tt><tt>=Sing</tt> (5235; 100%), <tt><a href="en_ewt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (5235; 100%), <tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (3880; 74%).

`AUX` tokens may have the following values of `Person`:

* `1` (363; 7% of non-empty `Person`): <em>am, was</em>
* `3` (4872; 93% of non-empty `Person`): <em>is, was, has, 's, does, s, ’s, `s, ai, gets</em>
* `EMPTY` (10177): <em>be, are, will, can, have, would, do, were, been, could</em>

<table>
  <tr><th>Paradigm <i>be</i></th><th><tt>1</tt></th><th><tt>3</tt></th></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>was</em></td><td><em>was</em></td></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>am</em></td><td><em>is, 's, s, ’s, `s, ai, i, se</em></td></tr>
</table>

### `VERB`

2313 <tt><a href="en_ewt-pos-VERB.html">VERB</a></tt> tokens (8% of all `VERB` tokens) have a non-empty value of `Person`.

The most frequent other feature values with which `VERB` and `Person` co-occurred: <tt><a href="en_ewt-feat-Mood.html">Mood</a></tt><tt>=Ind</tt> (2313; 100%), <tt><a href="en_ewt-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (2313; 100%), <tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt> (2197; 95%).

`VERB` tokens may have the following values of `Person`:

* `1` (11; 0% of non-empty `Person`): <em>was, am</em>
* `3` (2302; 100% of non-empty `Person`): <em>is, has, was, says, 's, makes, seems, needs, looks, comes</em>
* `EMPTY` (26095): <em>have, get, know, had, go, do, want, said, see, going</em>

<table>
  <tr><th>Paradigm <i>be</i></th><th><tt>1</tt></th><th><tt>3</tt></th></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Past</tt></tt></td><td><em>was</em></td><td><em>was</em></td></tr>
  <tr><td><tt><tt><a href="en_ewt-feat-Tense.html">Tense</a></tt><tt>=Pres</tt></tt></td><td><em>am</em></td><td><em>is, 's, s, ’s</em></td></tr>
</table>

`Person` seems to be **lexical feature** of `VERB`. 100% lemmas (429) occur only with one value of `Person`.

## Relations with Agreement in `Person`

The 10 most frequent relations where parent and child node agree in `Person`:
<tt>PRON --[<tt><a href="en_ewt-dep-nmod-npmod.html">nmod:npmod</a></tt>]--> PRON</tt> (3; 100%),
<tt>AUX --[<tt><a href="en_ewt-dep-conj.html">conj</a></tt>]--> AUX</tt> (1; 100%),
<tt>PRON --[<tt><a href="en_ewt-dep-case.html">case</a></tt>]--> VERB</tt> (1; 100%).

