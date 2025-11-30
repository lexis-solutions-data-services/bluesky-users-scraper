# Bluesky User Search Scraper

![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/bsky.png)

## What is the Bluesky User Search Scraper?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.4` |
| **Last Update** | Nov 30, 2025 |

---



The Bluesky User Search Scraper is a web scraping tool that allows you to scrape Bluesky user search results. It can be used programmatically obtain public data of a profile given a search query.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/hJKFXeESILvLy5GBC/QVKXCNU1HXW69FOWH-Bluesky-Logo.png" alt="Bluesky Users Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/bluesky-users-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## 🔎 Using the Actor as a Bluesky Profile Matcher

Do you have a list of users in your database and want to match them with their Bluesky profiles? Simply enter the name of the user from your database, and the scraper will return matching Bluesky profiles.

## 🔦 Using the actor as a Bluesky Profile Finder

Find a public Bluesky profile by entering the profile URL. The scraper will return the profile data in JSON, XML or CSV format.

## 💎 Using the actor as a Bluesky Profile Enricher

The Bluesky User Search Scraper can be used to enrich your existing user database with Bluesky profiles. You can connect your backend to the actor via API and automatically enrich your user database with Bluesky profiles.

## What data can the Bluesky User Search Scraper extract?

The Bluesky User Search Scraper can extract the following data from Bluesky user search results:

- ID
- Name
- Username
- Description
- Profile Image
- Profile URL

## What use cases does the Bluesky User Search Scraper?

- 👍 **Profile Matching** - you can use the Bluesky user to enrich your existing user database with Bluesky profiles. This can be useful for matching users across different platforms.
- 📈 **Market Research** - you can use the Bluesky user to obtain data about your competitors' customers. This can be useful for market research and competitor analysis.
- 📊 **Lead Generation** - you can use the Bluesky user to understand your target audience better. This can be useful for lead generation and sales.

## How to use the Bluesky User Search Scraper?

1. Create a free Apify account
2. Open Bluesky User Search Scraper
3. Enter a search query
4. Click Start and wait for the results
5. Download the results in JSON, XML or CSV format or connect the actor to your backend via API

## 📥 Input

To run the actor, simply enter search query string, and a limit of profiles to scrape.

# 📤 Output

The results are stored in the default dataset associated with the actor. Each item is an ad, having the following format:

```json
{
  "id": "did:plc:iojrdmvzewew5detpq3pu7gd",
  "avatar": "https://cdn.bsky.app/img/avatar/plain/did:plc:iojrdmvzewew5detpq3pu7gd/bafkreiaqnm7vomeqqzrcvaesp35umuo62xqwmd57oowmzju6stxtn5v7uq@jpeg?f=.jpeg",
  "displayName": "Adrian Bradley",
  "username": "adrianbradley.bsky.social",
  "description": "Broadcast Journalist, podcast producer and audiophile. Produce podcasts for the New Statesman. Love theatre, Eurovision, otters and jazz hands. He/him"
}
```

## Why use the Bluesky User Search Scraper?

- ⚡️ **Fast** - The scraper is fast and efficient, allowing you to scrape profiles in a programmatic way.

- 🤙 **Easy to use** - The scraper is easy to use and requires no coding knowledge. All you need to do is input the query you want to scrape and the scraper will do the rest.

- ☑️ **Well-Maintained** - The scraper is maintained by the Lexis Solutions team, ensuring that it is always up-to-date and working properly.

## FAQ

- **Is Scraping Bluesky Profiles Legal?**

  The current scraper only scrapes public data from Bluesky profiles. This means that the data is publicly available and can be accessed by anyone. However, we recommend that you check Bluesky's Terms of Service before using the scraper.

- **How much does it cost?**

  The cost for using the Bluesky User Search Scraper is shown on the top of this page. You can also check the Apify Store page for more information.

## Related Scrapers by Lexis Solutions

- [Facebook User Search Scraper](https://apify.com/lexis-solutions/facebook-user-search-scraper)

- [Bluesky Posts Scraper](https://apify.com/lexis-solutions/bluesky-posts-scraper)

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
