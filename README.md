when I visit `http://localhost:3000/?code=123456`,
it always redirect to `http://localhost:3000/#/dashboard` and the query string `?code=123456` is missing.

is it a angular2 bug?



===updated===
I know my mistake now.

the url I visit is http://localhost:3000/?cc=1111#/dashboard/123

the right url is http://localhost:3000/#/dashboard/123?cc=1111
