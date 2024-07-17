# FIL-B Painpoints Tracker

**Description:** capturing key operations for FVM DX team and collaborating working groups

**Objective:** set the right expectations to provide adequate timelines for deliverables, capture cross-collaborative processes to deliver the best solutions for FVM dev community.

## Triage FVM pain points and find resolution

#### Capture the pain points from developers, builders, investors, ecosystem partners, other PL teams

<table><thead><tr><th><p><strong>Feedback task</strong></p></th><th><p><strong>Process</strong></p></th><th><p><strong>Who/Turnaround time</strong></p></th></tr><tr><th rowspan="2"><p><strong>Dev community feedback on Slack.</strong> Channels that are monitored:</p><ul><li>#fil-builders (DX monitors)</li><li>#fil-net-calibration-discuss (DX monitors)</li><li>#fil-fvm-dev (Eng monitors)</li></ul></th><th><a id="kix.1py0cw8ccdct"></a><p>React with 👀(fvm-dx-tracking) emoji on <strong>Slack</strong>, to capture message in our <a href="https://airtable.com/shru91CTnjzFskYxk">Airtable</a>.</p><p>Rotational duty with DX team to be on-call one day of the week to help community on slack, discord, Q&amp;A on Github community/discussion.</p><ul><li>Mon: Longfei</li><li>Tue: Sarah</li><li>Wed: Matt</li><li>Thu: Zak</li><li>Fri: Robert</li></ul></th><th><p>FVM DX, Product, Engineering, Ecosystem (use the emoji only for builder feedback)</p></th></tr><tr><th><p>DX to check Airtable daily and filter for either DX or Product to triage. Product to triage on weekly cadence.</p><p>DX will bias to action and surface any P0 and urgent issues to relevant teams for resolution ASAP.</p><p>For non-P0 and less urgent issues, DX &amp; Product will triage within 1-3 days, depending on bandwidth.</p><p>Once a resolution is reached, these messages will be cleared from the Airtable.</p></th><th><p>FVM DX (current DRIs: Longfei, Robert)</p><p>Triaged in the following turnaround time:</p><ul><li>P0 = 24 hr</li><li>P1, P2 = 24 - 72 hrs</li></ul></th></tr><tr><th rowspan="2"><p><em>Ascent Github Painpoint tracker, captures dev community feedback from Slack. It is a more synthesized version of that.</em></p><p><a href="https://github.com/orgs/filecoin-project/projects/82/views/26"><strong>Ascent Github Painpoint tracker</strong></a><strong> logs issues to resolve for:</strong></p><ol><li>Dev pain points (e.g. broken features, docs requirements, testing issues)</li><li>Product strategy pain points (e.g. feature requests, questions about scope, and non-urgent but important considerations)</li><li><a href="https://www.notion.so/pl-strflt/FVM-Partner-Feedback-Github-Process-65ddb8823f43430eb931fdc70fce7a88">Partner feedback process</a> (eg for outercore, ecosystem, and external stakeholders)</li></ol></th><th><p>DX, Product, Engineering and Ecosystem can log a dev/product/ecosystem partner pain point, as an issue in the Github tracker.</p><p>Teams can log for each other (e.g. DX can log for Product). The tagged Assignee or Pillar, will determine who owns the resolution of that issue:</p><ul><li>Pillar = Builders is for DX</li><li>Pillar = Product is for Product</li><li>Pillar = Ecosystem / Partners is for Ecosystem</li><li>Pillar = Platform is for Engineering</li></ul><p></p><p><em>Example </em><a href="https://github.com/orgs/filecoin-project/projects/82/views/26?pane=issue&amp;itemId=24970512"><em>here</em></a><em> with Lotus team.</em></p><p>Additionally, DX will help triage the Airtable above and decide what to log as an issue on the tracker, and assign accordingly. We will bias to action and implement <a href="#_t9pobdybajil">fixes</a> ASAP.</p><p>Issues to be logged with the following format in Description:</p><ul><li>Breakage (issue description and link to all available evidences/original userl posts as much as possible)</li><li>Component related to (which feature etc.)</li><li>Impact on devs (why is this important)</li><li>Ideal solution (what’s the happy path)</li></ul><p>Priority will also need to be tagged:</p><ul><li>P0 = crucial, needs work now</li><li>P1 = important but can wait</li><li>P2 = useful but not important for now</li></ul><p>Issues to be logged and highlighted in #fvm-core-team Slack channel to give visibility to stakeholders. Things can get buried in Github.</p><p>Note pinned message on <a href="https://filecoinproject.slack.com/archives/C04N0FSJ11P/p1688005894236429">fvm-outercore-team</a> for partner feedback process. As mentioned there:</p><ul><li>Stakeholders can use <a href="https://www.notion.so/pl-strflt/Partner-Feedback-Github-Process-65ddb8823f43430eb931fdc70fce7a88">the following guide</a> to flag issues with the FVM team (<a href="https://github.com/filecoin-project/fvm-pm/issues/new?assignees=&amp;labels=Partner+feedback&amp;projects=&amp;template=partner-feedback---feature-request.md&amp;title=">direct link for new issue feedback is here</a>)</li></ul><p>Discussion should continue on the Github issue’s thread.</p></th><th><p>FVM DX, Product, Engineering, Ecosystem</p><p>Resolution turnaround times will vary depending on issue</p><p>Other resources:</p><ul><li><a href="https://www.google.com/url?q=https://www.notion.so/pl-strflt/Product-Management-Process-H2-2023-WIP-fc9a25c6c98849f08309e5f78614382a&amp;sa=D&amp;source=docs&amp;ust=1686740815023273&amp;usg=AOvVaw34HzDoXlZ4YvE-qfNkhSYY">Product process doc</a></li><li><a href="https://miro.com/app/board/uXjVM_WJ-Pw=/">Process flow</a></li><li><a href="https://miro.com/app/board/uXjVM_WJ-Pw=/">Product Miro board</a></li></ul></th></tr><tr><th><p>Process to upvote different issues is present with `Upvotes` field</p></th><th><p>FVM team</p></th></tr><tr><th><p><strong>Tracking resolution of issues.</strong></p></th><th><p>Cadences to review outstanding issues tagged to the following pillars and push for resolution:</p><ul><li>DX = DX weekly sync, Product &lt;&gt; DX weekly triage</li><li>Product = Product weekly sync, Product &lt;&gt; DX weekly triage</li><li>Ecosystem = Ecosystem Standup weekly sync, cross-WG weekly</li><li>Engineering = Engineering huddle weekly, cross-WG weekly</li></ul><p>Once the issue owner completes the resolution of the issue, close it.</p></th><th><p>Owner of issue</p></th></tr><tr><th><p><strong>Public visibility to devs on issues being worked out/resolved</strong></p><p>Objectives:</p><ul><li>Support open source culture</li><li>Give devs visibility to WIP</li><li>Encourage dev support to issues</li></ul></th><th><p>Roundup post on <a href="https://fvm-forum.filecoin.io/">Filecoin forum</a> + amplify on Slack?</p></th><th><p>FVM DX (Current DRIs: Longfei, Robert)</p></th></tr></thead></table>

#### DX ways to resolve issues (that are assigned to Builders pillar)

- Docs issue = create an issue for docs & write content for a PR.
- Common FAQ = create article under [Github:community/Discussion/Q&A](https://github.com/filecoin-project/community/discussions/categories/q-a)
- Product feature = handover to Product to own, input on solution design and timeline
- Engineering feature = handover to Engineering to own, input on solution design and timeline
- Engineering bug = log an issue to corresponding repos (e.g. Lotus, built-in actor, fvm-ref)

## FVM DX support to hackathons

In addition to Builders Funnel team runs hackathons, process [here](https://docs.google.com/document/d/101NQn-vEjGMQqse_ccwP2Qaf0YH9yMHnb1lZny4QNOQ/edit#).

Retro reports found [here](https://airtable.com/shrMRgnwFYnMlHyvc). From the retro reports, any found issues will follow [pain point tracker](#_z6mr2ogeiacp) process.
