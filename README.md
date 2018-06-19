# Splunk Dashboards
Splunk dashboard source files

<h3>ssh-bruteforce-tracking</h3>
A dashboard for tracking SSH bruteforce attempts.  Several items are linked to allow for point and click drilldown.
Requirements:
- linux /var/log/secure indexed as "secure"
- "ip" and "username" extracted fields from SSH attempt events
