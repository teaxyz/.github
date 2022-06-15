# Contributing

We love open source and are blown away when people volunteer their time and
proffer us code as pull requests. We must emphasize however that the most
important thing to us is the quality and robustness of our products.

Thus we kindly request you provide us with concise, minimal pull requests.
This means:

1. Keep them on point[^1]
2. The shorter the better[^2]
3. Avoid moving code around unnecessarily[^3]
4. Force push rather than merge when `main` advances[^4]
5. Add lots of comments (but not too many[^5])
6. Mark in-progress PRs as *drafts*
7. *For documentation*, use newlines at natural breaks, ie. sentences[^7]

[^1]: We know it’s hard to avoid tweaking this and that as you work, but
    unfortunately anything that is not specific to the purpose of the pull
    request is distracting and increases the likelihood the review will be
    delayed or we’ll make mistakes.
[^2]: Reviewing code is hard, if you keep the amount to
    review low we’ll review faster and there’s less chance we’ll make mistakes
[^3]: It bloats up the diff and makes it hard to be sure that nothing has
    regressed in the code movements.[^refactors]
[^4]: Merge commits are instructive when merging pull requests, but they are
    a hindrance during the pull request review period.
[^5]: If the code is clear, don’t comment it: you’re just reducing clarity,
    but if it not’s clear *comment it!* Otherwise you’re also reducing
    clarity!
[^7]: `git` diffs at newlines, breaking at human contexts ensures readable diffs and expedient review.

[^refactors]: Don’t get us wrong: We love refactors!
    Over time code gets warts and you might well be the beautician we need.
    If you want to refactor please submit the refactor as an *entirely separate
    pull request*!
