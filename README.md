# Whole Leader Assessment

The Whole Leader Assessment experience for Dr. Teneka Miles (The Covenant Counselor): 104 questions across four chapters, ending in the integrated Whole Leader profile.

- Chapter 1, Your Wiring (temperament, attachment wiring, threat response)
- Chapter 2, Your Faith
- Chapter 3, Your Relationships (relational health and relational profile)
- Chapter 4, Your Emotions (awareness, expression, regulation, recovery)
- Whole Leader profile: Whole Leader Index and band, four-domain chart, strongest and growth domain, Leadership Signature (shareable), signature pattern, and the safety block when flagged

All questions, scoring rules and result text follow the Whole Leader Assessment Complete Build Guide.

A single static page (`index.html`), no build step. Deployed on Vercel; every push to `main` redeploys.

When embedded in the Content Creator Machine funnel, the page posts its results to the parent page (`type: "complete"`). Fields: temperament, attachment, threatResponse, neuroScore/neuroBand, spiritualScore/spiritualBand/spiritualGrowthArea, relationalScore/relationalBand/relationalProfile/relationalGrowthArea, emotionalScore/emotionalBand/emotionalGrowthArea, wholeLeaderIndex/wholeLeaderBand, strongestDomain, growthDomain, focusDomain, leadershipSignature, signaturePattern, safetyFlag, chaptersCompleted, version ("full").

Add `?demo=1` (or open the page outside the funnel) to show the "Demo: auto-fill answers" link for quick previews.
