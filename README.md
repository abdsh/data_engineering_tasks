# data_engineering_tasks
for running codes in this repo you should have python (preferably anaconda distribution) on your server/pc and install libs in requirements.txt.

```sh
pip install -r requirements.txt
```
## For question 1
<p>you should have postgresql up and runnig</p>
<p>and create two datavase with names oltp_db , dwh_db<\p>

```sh
CREATE DATABASE oltp_db;
CREATE DATABASE dwh_db;
```
you should run following file in order :

- create_oltp.ipynb
- create_dwh.ipynb
- jobs for filling dimension and fact tables.ipynb
- answers_ for_question1.ipynb

