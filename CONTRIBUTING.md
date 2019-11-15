# Contributions
First, let me say thank you for wanting to contribute to this open source project! There are 2 ways to add a company to this project, but either way, you must include a __company__ or __brand name__, a __description__ of why they are complicit, and a __source url__ so we can verify your claim.


## Non-Tech-savvy contributions
If you are not tech savvy, then open an issue for a new [feature request](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue).


## Tech-savvy contributions
If you are tech savvy, create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) with the company you want to add. All changes should happen in index.js

Append a new JSON object to the bottom of the `TrumpConflictedCompanies` array

_New Business Example_
```
{
      "id": "aUniqueNameForThisBrand",
      "brand": "The Brand Name",
      "description": "A brief description of why this brand is complicit.",
      "source": "A URL that can be used to verify the claims in the description.",
      "sourceDescription": "A brief description of the source url.",
},
```
