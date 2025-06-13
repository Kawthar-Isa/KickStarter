# KickStarter
## 1. Data Handling Summary
- Reformatted Columns:
   funded date converted to proper datetime format.
- Split Columns:
   location was split into city and state using regex to isolate US states and cities.
- Handled Missing Values:
   Rows with missing location were deleted.
- Added New Columns:
   success: binary column (1 = successful, 0 = otherwise).
   goal_bucket and backer_bucket: groupings for easy segmentation.
   funded_ratio: actual funded percentage in percentage form.
## 2. Data Dictionary
  datadictionary-kickstarter file
## 3. Quantitative Data Analysis
- Summary Insights:
   Success Rate: ~36%–38% of all projects were successful (based on status analysis).
   Highest Pledged Categories: Film & Video, Technology, and Music led total pledged amounts.
   Backer Count Distribution: Most projects had < 100 backers; only a small % exceeded 1,000.
- Limitations in Data:
   No access to real-time updates or completion reports after project funding ends.
   No demographic data (age/gender of creators or backers).
   Lacks social media metrics or marketing strategies used (which impact success).
   No distinction between individual vs. team-run campaigns
## 4. Qualitative Analysis & Recommendations
- What’s the best campaign duration?
   Optimal campaign lengths are 20–30 days.Very short campaigns may not build enough momentum.Long campaigns (>45 days) often lose urgency and engagement.Medium-length campaigns had the highest success rates in analysis.
  
- Ideal pledge goal?
   Most successful campaigns had goals between $1,000 – $10,000.Lower goals (< $1k) might succeed easily but lack scale.High goals (> $50k) had low success unless backed by a strong audience or media presence.

- Best time to launch (Month/Day/Time)?
   Best Months: March to May, and September (backer engagement is high).
   Worst Months: December (due to holidays).
   Best Days: Tuesday to Thursday.
   Best Time: Launch early in the day (8–11am EST) to get maximum visibility.

