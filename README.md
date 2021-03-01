# Digital-Reason-News
This project is a playground for Umbraco headless called "reason digital news"

## Getting started

I'm using .NET 4.8, so make sure you have it on your machine and this should build with any issues :)
I'm not new to the concept of headless, but this is actually the first time I'm implementing it
so I used this as an opportunity to play around with it.

At first, I followed the instructions of the requirements listed on the pdf
then I saw this package https://github.com/mattbrailsford/umbraco-headrest
it was really easy to use, and I liked the idea, after playing some time with the package
unfortunately, I didn't achieve what I wanted :/ (id's for the news items instead of the names)
for some reason, the content finder/routing wasn't working properly.

But I wanted this /api/ behaviour in the routes, so I developed 2 options:

1) Hijack Controllers & Data object (REQUIREMENT)
- /
- /news/
- /news/coronavirus-biden-s-1-9tn-covid-relief-bill-passes-house-vote/


2) More realistic approach with custom routing and content finder for news items (SUGGESTION)
- /api/
- /api/news/
- /api/news/1068/

NOTE: I changed the grid in favour of blocks I think this new concept is more solid and editor friendly.

## License

Copyright &copy; 2021
Licensed under the MIT License.