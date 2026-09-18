# Decision Points Rationale - TruthLens

### DP1 · Feed Order
We implemented Risk-Weighted Recency sorting. Unverified claims flagged as "High Risk" appear at the top of the feed, followed by the newest posts. This prioritizes rapid triage for viral, high-impact misinformation before it causes real-world harm.

### DP2 · Visibility
Unverified claims remain publicly visible immediately but carry clear warning badges and risk flags. Censoring claims entirely creates informational vacuums that encourage user distrust, whereas immediate visibility paired with warning labels mitigates risk transparently.

### DP3 · Editing
Submissions are strictly immutable after posting. Allowing post-submission editing enables malicious actors to modify claims after auto-flagging, which corrupts audit trails and undermines fact-checker workflow integrity.
