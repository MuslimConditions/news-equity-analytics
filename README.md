# news-equity-analytics
Tools to analyze news feeds for equity in coverage.

This is a Node.js package to parse a news organization's RSS feeds and analyze its text for arrays of key topics – whether they're towns, or politicians, or sports teams – to generate data on how equitably journalism institutions allocate their attention.

Results are saved in a PostgreSQL database described by the `database.sql` file. This code can be run locally, or scheduled to run daily on a hosted Node.js server.  
