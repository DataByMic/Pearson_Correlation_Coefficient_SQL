# Pearson_Correlation_Coefficient_SQL
A investigation into how to better corroborate or reject gut feeling hypothesis from non technical stakeholders..

The idea behind exploratory data analysis in theory is about exploration, but in reality, it is based on stakeholder X's theory of what is driving something. How can we validate these ideas before having to create dashboards, excel exports out of data warehouses, which allow the opportunity for data to be further "massaged" to fit a narrative.

This is where the Pearson Correlation Coefficient comes in. This is not a new concept, but I have not seen its application in such a way in my experience before.

I have wrote a query which explores the relationship between 2 variables, which can be easily adapted. Furthermore if there is interesting insights, it can be further developed to deploy answers over other categorical values, for example by rolling the results up against countries.

This is meant to be a useful for quick investigations over a large dataset within a data warehouse/sql server and will use only basic functions which allows it to be used across any variation of SQL.
