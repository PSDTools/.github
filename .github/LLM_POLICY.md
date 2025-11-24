# Large Language Model (LLM) Policy

LLM use is a divisive topic right now, even among our team.
In order to ensure that our codebases remain high-quality, our contributors remain enlightened, and our licenses remain upheld,
we've decided to, rather than outright ban LLM usage—as some of us would prefer,
institute the following policy:

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL"
in this document are to be interpreted as described in [RFC 2119][rfc2119].

1.  We want human creativity.
    The design of a feature **SHOULD** be driven by humans, not by LLMs.
    You **MAY**, however, use an LLM to refine existing ideas
    (e.g., give an LLM a spec and ask it for conceptual or grammatical feedback).
2.  Humans are ultimately responsible.
    You **MUST** be able to explain and/or defend every non-generated line of code you contribute
    (generated here meaning via traditional means such as scaffolders).
    If you're unable to do so, you **SHOULD NOT** have delegated it in the first place.
    By extension, you **MUST NOT** anthropomorphize an LLM by adding it as an author.
    Using an LLM is not an excuse for creating poorer code;
    rather, if they work as purported, they should be helping you write better code
    so that we can hold our code to higher standards.
3.  You **MUST** disclose all LLM use.
    If you do not, your contribution **MUST** be categorically rejected.
4.  Every interaction made as a user (e.g., pull requests, issues, comments, etc) **SHOULD** be written entirely by you;
    the exceptions being Grazie, Grammarly, and adjacent tooling _when used non-generatively_
    (i.e., purely for checking grammar, not for rewriting/rephrasing sentences).
    It's OK if you don't have perfect grammar!
    We've come to appreciate authenticity far more—we'd much rather have to ask for clarification than read an LLM-generated text.
5.  You **SHALL NOT** ask for help debugging LLM-generated code.
    If, in your own attempts to debug the code, you haven't fully rewritten it, you haven't put in sufficient effort debugging it yourself.
    We respect you and your time, please respect us back.
6.  You **MUST** consider licensing.
    While some of us view LLMs as copyright laundering machines, we'll assume that they're granted fair-use for the sake of this document.
    However, you **MUST** be aware of public code matches.
    If code you contribute is elsewhere licensed incompatibly and is legally non-trivial, you **MUST NOT** submit it.
7.  If _you_ know how to use an em-dash properly, go right ahead; the same goes for en-dashes.
    Emojis, on the other hand, **SHOULD** be used sparingly.

> This policy was originally [drafted][draft] by [Elisha Dukes][lishaduck] and represents the ratified views of the team.
> This work is licensed under [CC BY-SA 4.0][cc-by-sa-4].

[cc-by-sa-4]: https://creativecommons.org/licenses/by-sa/4.0/
[draft]: https://gist.github.com/lishaduck/cfa664e8e8303b0f43a6c0a2293bf17b
[lishaduck]: https://github.com/lishaduck
[rfc2119]: https://datatracker.ietf.org/doc/html/rfc2119
