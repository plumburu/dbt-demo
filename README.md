## Installing env
```
 $ pip --version
 $ pip install --user pipenv

 
python -m venv dbt-env             # create the environment
dbt-env/Scripts/activate         # activate the environment

pip install dbt-core  #install dbt
pip install dbt-snowflake #snowflake adapter  

 in case of errors download source and install 
git clone https://github.com/dbt-labs/dbt-core.git
cd dbt-core
pip install -r requirements.txt

upgrade 
pip install --upgrade dbt-snowflake
```

Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices
