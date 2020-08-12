# ALSDataEngineer

Dataset
<br>A dataset simulating CRM data is available in some public AWS S3 files:
<br>Constituent Information: https://als-hiring.s3.amazonaws.com/fake_data/2020-07-01_17%3A11%3A00/cons.csv
<br>Constituent Email Addresses: https://als-hiring.s3.amazonaws.com/fake_data/2020-07-01_17%3A11%3A00/cons_email.csv
<br>    Boolean columns (including is_primary) in all of these datasets are 1/0 numeric values. 1 means True, 0 means False.
<br>Constituent Subscription Status: https://als-hiring.s3.amazonaws.com/fake_data/2020-07-01_17%3A11%3A00/cons_email_chapter_subscription.csv
<br>    We only care about subscription statuses where chapter_id is 1.
<br>    If an email is not present in this table, it is assumed to still be subscribed where chapter_id is 1.

Output :  People.csv, Acquisition_facts.csv

Requirements : python packages -> pandas==1.1.0 
