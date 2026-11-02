Source: https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad
Retrieved: 2026-11-02

# Become a WB seller from abroad

## If your company is based outside Russia and you want to sell on Wildberries and automate with the WB API, here is the path — from becoming a seller to your first token.

166

Publication date: 01.07.2026

![content](https://static-basket-02.wbbasket.ru/vol20/dev-portal/17864475035162574192346f95.svg)

## [Selling on Wildberries from another country](https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad\#selling-on-wildberries-from-another-country)

**If your company is based outside Russia, selling on Wildberries may still be open to you — and once you're a seller, you can run your day-to-day operations through the WB API: uploading products, setting prices, receiving orders, and pulling analytics.**

The WB API is the developer interface to your seller account. Before you can use it, you need an account to connect to. What differs from country to country are the registration details — more on that below.

#### One path, three steps

Access to the API goes through a regular seller account — the usual route for Wildberries sellers. In short: become a seller, open your account, and create a token inside it. Everything you do with the API starts from that token.

* * *

## [Step 1. Become a seller](https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad\#step-1-become-a-seller)

Registration is the entry point — the WB API only works once you have a seller account behind it. How you register depends on where your business is set up:

- **A local business.** If you have (or are ready to set up) a company, sole proprietorship, or self-employed status registered in Russia, you go through standard seller registration.
- **A cross-border model.** You stay a foreign company and sell under Wildberries' cross-border model. It is available for a number of countries, and the current list is shown to you during registration.

We are keeping this deliberately high-level: registration requirements, the documents you provide, and how settlements and logistics work depend on your country and are set per market. Do not assume the details are the same everywhere — check what applies to you when you register.

Marketplace rules and seller instructions live in the seller help center — it is also available [in Chinese](https://seller.wildberries.ru/instructions/ch/ch/categories).

* * *

## [Step 2. Get access to your account](https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad\#step-2-get-access-to-your-account)

Once you are registered, you sign in to your seller account. This is where you manage your catalog, orders, prices, and — importantly for developers — where API access lives. Everything the API can do is scoped to this account: the token you create later carries the data categories you grant it, within what your account allows.

* * *

## [Step 3. Issue an API token](https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad\#step-3-issue-an-api-token)

**The token is what authorizes your API requests.** You create it inside your seller account, choose which data categories it may access, and then send it in the `Authorization` header of every request. A token is valid for 180 days after you create it.

#### What your token can access

Connecting follows the standard seller flow — what varies is the set of data categories your token was granted, which decides the methods it can call. Treat the documentation as the reference for what a given method does, and check your token's scope for what it can access.

* * *

## [Where to read more](https://dev.wildberries.cn/news/321/become-a-wb-seller-from-abroad\#where-to-read-more)

The mechanics — how tokens work, which categories exist, and every method with its parameters and response — are in the documentation. Start with the Authorization section on the General documentation page. And once your token works, the fastest way forward is the hands-on quick start — it takes you from a token to a real response in about 15 minutes.

[Make your first request in 15 minutes](https://dev.wildberries.cn/news/328)

[Authorization in the documentation](https://dev.wildberries.cn/en/docs/openapi/api-information#tag/authorization)

#### Building a service on top of the WB API?

If you're a SaaS provider and need authorized access on behalf of your clients, write to [business-solutions@rwb.ru](mailto:business-solutions@rwb.ru).

We use [cookies](https://legal.wildberries.ru/privacypolicy/country/ru/lang/en/#anchor-7) to analyze how you use the site and to improve it

DeclineAccept
