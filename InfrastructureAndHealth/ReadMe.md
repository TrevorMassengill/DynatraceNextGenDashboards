## Requirements
* Dynatrace SaaS

## Recommendations
* Dashboard requires an OS key value tag on hosts. Looks for OS:Linux or OS:Windows.
* Critical and Warning level problems are determined by the title of the problem, if "Critical" or "Warning" are in the name respectively.
* Update the markdown tiles with relevant links and company logo.

## Notes
* The metric tiles have filters to only pull entities whose metrics exceed a certain value, reduces likelyhood of sampling and saves on performance.
* Health tiles represent how many entities have problems, or no problems.
* Availability tile uses past 3 minutes in an attempt to reduce sampling.
* Metric results are sampled if too many entities or too large of a timeframe is used.
