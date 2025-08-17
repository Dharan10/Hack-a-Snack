# Task: Identify the vulnerability in this query.

SELECT * FROM users WHERE username = 'admin' AND password = ' ' OR '1'='1';
