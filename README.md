# splunk-brute-force-detection
## Splunk Brute Force Detection Lab

A hands-on brute force detection project using a custom-built authentication log dataset and a local Splunk instance.

## What I Did

Created a custom CSV dataset simulating employee login activity alongside a brute force attack scenario. Loaded the data into Splunk and ran SPL queries to identify the attacker based purely on behavioral patterns in the logs, no prior knowledge of the attacker required.

- Identified a suspicious IP with 8 events vs. 1 for all legitimate users
- Confirmed 7 failed login attempts followed by a successful login
- Built a threshold-based detection query to automatically flag brute force behavior
- Reconstructed the full attack timeline in chronological order

## Tools Used

Splunk Enterprise, SPL (stats, sort, where, table), custom CSV dataset

The full investigation report is included above with screenshots and SPL query explanations.
