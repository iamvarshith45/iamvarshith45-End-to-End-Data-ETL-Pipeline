# iamvarshith45-End-to-End-Data-ETL-Pipeline
built a data pipeline to analyze daily agent performance using call logs, agent  and login disposition data.
the system merges these datasets on key fields (agent_id, org_id, call_date) ensuring no data loss. 
We engineered features like total calls, unique loans contacted, connect rate, average call duration, and agent presence. 
The logic gracefully handles mismatches and missing data. 
A summarized report is generated for each agent and saved as agent_performance_summary.csv. 
Additionally, we format a Slack-style performance message highlighting key metrics including top performer, average duration, and overall connect rate. This solution enables quick daily insights for operations and team leads.
