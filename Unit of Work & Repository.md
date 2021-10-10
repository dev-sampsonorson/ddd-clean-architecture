# Unit of Work & Repository

Should we implement these patterns?
It isn't always the best choice, because:

- EF Core insulates your code from database changes
- DbContext acts as a unit of work
- DbSet acts as a repository
- EF Core has features for unit testing without repositories

You can use these patterns if;
- You want to application from ORM
- You ensure you go through Order to reach OrderDetails for example  