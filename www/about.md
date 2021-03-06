# About xd.saul.pw

xd.saul.pw is a system I put together to practice my data pipeline and preservation skills.
It collects daily crosswords from several sources and converts them into .xd, a plain-text format designed for maximum data flexibility.
It then compares them against the rest of the crosswords in the corpus, and generates this static website.

I call this a 'cloud capsule'.
It's a long-form web service that curates a longitudinal dataset for future crossword scholars.
Acquiring historical crosswords requires focused effort and tedious cleaning that few people are willing to do for such trivial data.

I tried to design this capsule to be self-sustaining, which for me means a robust and low-maintenance system that can run in perpetuity at very little cost.
To this end, I chose a kind of ‘long serverless’ architecture which does daily batch processing, rather than a continuous server or a newfangled collection of asynchronous cloud services.

Ideally this crossword cloud capsule would survive until all of the crossword data can be released publicly.
But as it will probably fall short of this goal, I took great care with the data formats and organization, so that the curated data could be easily salvaged by a capable and responsible steward.

In the meantime, all [public crossword data can be downloaded](/data#download) for free, and the entire [source code is available on Github](http://github.com/century-arcade/xd).


Please send all suggestions, offers, and complaints to [xd@saul.pw](mailto:xd@saul.pw).

Share and enjoy!

[Saul Pwanson](http://saul.pw)

### Many Thanks To

* Barry Haldiman, for collecting so diligently;
* David Steinberg and the [Pre-Shortzian Puzzle Project (PSPP)](http://www.preshortzianpuzzleproject.com), for inspiring me;
* Jim Horne, Jeff Chen, and [xwordinfo.com](http://xwordinfo.com), for frustrating me so nicely;
* Kevin McCann and [cruciverb.com](http://cruciverb.com), for useful discussions on crossword creation;
* [Timothy Parker](https://en.wikipedia.org/wiki/Timothy_Parker_(puzzle_designer%29) and Ollie Roeder, for providing some [drama](http://fivethirtyeight.com/features/a-plagiarism-scandal-is-unfolding-in-the-crossword-world/);
* Joseph Gratz at [Durie Tangri LLP](http://durietangri.com), for his generous legal counsel;
* my friends and family, for supporting me in my crazy projects;
* and of course, all the constructors, editors, and publishers, for producing such great puzzles in the first place!

