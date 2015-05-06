Wildcard for LIKE in MySQL
===================

For many years I lived under the thought that you could only use a `%` in a LIKE statement at the beginning and the end of the string. This is not so. A wildcard can be used anywhere within a string. Also learned of `_` to match a single character.

    mysql> SELECT 'David!' LIKE '%D%v%';
            -> 1
        
https://dev.mysql.com/doc/refman/5.0/en/string-comparison-functions.html
