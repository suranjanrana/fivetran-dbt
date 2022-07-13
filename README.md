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

[LINK](https://fivetran.com/docs/transformations/dbt/data-models/fivetran-log-connector-data-model)

Steps to follow:
- Create a file **_packages.yml_**
- Open fivetran logs from [link](https://hub.getdbt.com/fivetran/fivetran_log/latest/)  
- Copy to **_packages.yml_**  
- Then run the following command

```bash
$ dbt deps
```

Command to run the model:
```bash
$ dbt run --models fivetran_log
# This runs the models in the folder fivetran_log
```

```bash
$ dbt docs generate && dbt docs serve
# Opens a webpage that showas all the repo, model and dependecies along with lineage graph
```
