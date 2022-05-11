# data_engineering_tasks
<p>I assume you have a Linux workstation.</p>
<p>For running codes in this repo you should have python (preferably anaconda distribution) on your server/pc and install libs in requirements.txt.</p>

```sh
pip install -r requirements.txt
```
## For question 1
<p>you should have postgresql up and runnig</p>
<p>and create two datavase with names oltp_db , dwh_db</p>

```sh
CREATE DATABASE oltp_db;
CREATE DATABASE dwh_db;
```
You should run following jupyter notebook files in order :

- [create_oltp.ipynb](https://github.com/abdsh/data_engineering_tasks/blob/main/create_oltp.ipynb)
- [create_dwh.ipynb](https://github.com/abdsh/data_engineering_tasks/blob/main/create_dwh.ipynb)
- [jobs for filling dimension and fact tables.ipynb](https://github.com/abdsh/data_engineering_tasks/blob/main/jobs%20for%20filling%20dimension%20and%20fact%20tables.ipynb)
- [answers_ for_question1.ipynb](https://github.com/abdsh/data_engineering_tasks/blob/main/answers_%20for_question1.ipynb)

## For question 2
first you shoud have **MINIO** cluster up and running with **docker-compose**
<p>You also should download spark 3.2.0</p>
and set folloing varible in your shell

```sh
export SPARK_HOME=/PATH/TO/YOURE/spark3_2_0
export PATH=$PATH:$SPARK_HOME/bin
```
for connect spark to minio you also need to download following **JAR** files
and put then in your spark **jars** directory.

```sh
- aws-java-sdk-bundle-1.11.375.jar
- hadoop-aws-3.3.1.jar
```





