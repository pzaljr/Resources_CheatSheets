# Hofmannsven MySQL cheatsheet
https://gist.github.com/hofmannsven/9164408

# ORMs and You
https://www.reddit.com/r/PHP/comments/3cla9l/are_orms_inherently_limiting/
> 
The first tree really nails it though.  ORM's separate a bunch of foundation code from your app code, at the cost of default configuration not being finely tuned.  So you've gotta have someone who understands both your app and the ORM really well who can do the configuring of cache's and rules used when converting to the native DB language

> ORM is not a SQL alternative. They are not mutually exclusive choices

# Find a Column in any Table of a Database

```
select * from INFORMATION_SCHEMA.COLUMNS 
where COLUMN_NAME like '%clientid%' 
order by TABLE_NAME
```
