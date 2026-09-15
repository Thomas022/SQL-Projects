# SQL Multiple Tables Project

A collection of four SQL practice projects exploring how to combine related tables and answer analytical questions. The exercises cover ride-sharing, online communities, project staffing, and business reviews.

## Projects

### 1. Lyft Trip Data

Explore trip, rider, and autonomous vehicle data.

- Join trips with rider and car information.
- Combine rider datasets using `UNION`.
- Calculate average trip cost.
- Identify riders with fewer than 500 trips.
- Count active cars and find the two cars with the most completed trips.

**Tables:** `trips`, `riders`, `riders2`, `cars`

### 2. Multiple Tables with Reddit

Analyze fictional Reddit data to explore user activity, post scores, and subreddit popularity.

- Count subreddits and identify those with the most subscribers.
- Calculate the number of posts per user.
- Combine existing and additional posts.
- Find popular posts using a common table expression (CTE).
- Explore highest and average post scores by subreddit.

**Tables:** `users`, `posts`, `posts2`, `subreddits`

### 3. VR Startup Company

Explore employee assignments and staffing needs at a fictional virtual reality startup.

- Identify employees without a project.
- Find projects with no assigned employees.
- Determine which projects attract the most employees.
- Calculate remaining developer positions.
- Analyze employee personality types and project assignments.

**Tables:** `employees`, `projects`

### 4. Welp — Business Reviews

Combine business and review data to explore ratings and review activity.

- Compare results from `INNER JOIN` and `LEFT JOIN`.
- Identify businesses without reviews.
- Filter reviews from 2020 using a CTE.
- Rank reviewers by review count for businesses whose average rating is at or below the overall average business rating.

**Tables:** `places`, `reviews`

## SQL Skills Demonstrated

- **Combining tables:** `INNER JOIN`, `LEFT JOIN`, `CROSS JOIN`
- **Combining datasets:** `UNION`
- **Aggregations:** `COUNT`, `AVG`, `MAX`
- **Grouping:** `GROUP BY`, `HAVING`
- **Filtering:** `WHERE`, `IS NULL`, `NOT IN`
- **Ranking results:** `ORDER BY`, `LIMIT`
- **Query structure:** subqueries and CTEs with `WITH`
- **Date filtering:** `strftime`


## Purpose

Practice querying relational data across multiple tables and translating analytical questions into SQL.
