# Survey-Analysis
A data analysis guided project.

The assignment is to get the number of job openings using the GitHub Jobs API 

GitHub Jobs API allows anyone to query for the jobs based upon:

Technology like Python, MySQL; City like New York, Bangalore


Pagination
The API also supports pagination. /positions.json, for example, will only return 50 positions at a time. You can paginate results by adding a page parameter to your queries.

Pagination starts by default at 0.

Examples
https://jobs.github.com/positions.json?description=ruby&page=1

https://jobs.github.com/positions.json?page=1&search=code

GET /positions.json
Search for jobs by term, location, full time vs part time, or any combination of the three. All parameters are optional.

Parameters
description — A search term, such as “ruby” or “java”. This parameter is aliased to search.
location — A city name, zip code, or other location search term.
lat — A specific latitude. If used, you must also send long and must not send location.
long — A specific longitude. If used, you must also send lat and must not send location.
full_time — If you want to limit results to full time positions set this parameter to ‘true’.
