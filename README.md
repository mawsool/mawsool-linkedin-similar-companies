# Find Similar LinkedIn Companies

**Turn one LinkedIn company URL into the similar companies shown on that page, with name, description, location, and URL. $1 per 1,000 source companies.**

A page usually returns about 10 lookalikes. One source company is one charge. Send those URLs to Company Details or Company website and firmographics when you need the website and headcount.

This is the similar-companies block on the company page. It is not a custom lookalike model.

## Who is this for?

Outbound teams building a lookalike account list from a handful of customers.

## What does a row look like?

```json
{
  "inputUrl": "https://www.linkedin.com/company/example",
  "companyName": "Example",
  "similarCount": 10,
  "similarName": "Lookalike Co",
  "similarUrl": "https://www.linkedin.com/company/lookalike",
  "subtitle": "Software Development",
  "location": "United States",
  "success": true
}
```

## FAQ

### How many companies do I get?

Usually about 10 per source company. The count is whatever that page shows.

### Is one lookalike one charge?

No. The source company is one charge. The lookalike rows are included.

## Related Actors

Company website and firmographics for website, industry, and size. Company Details for the full page.

## Where to run it

Run the published Actor on Apify, or start from [mawsool.tech](https://mawsool.tech). This repository does not include the lookup address.
