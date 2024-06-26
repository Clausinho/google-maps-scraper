![Google Maps Scraper Feautred Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/google-maps-scraper-feautred-image.png)


<div align="center" style="margin-top: 0;">
  <h1>✨ Google Maps Scraper 🤖</h1>
  <p>💦 Find New Customers and Grow Your Buisness 💦</p>
</div>
<em>
  <h5 align="center">(Programming Language - Python 3)</h5>
</em>
<p align="center">
  <a href="#">
    <img alt="google-maps-scraper forks" src="https://img.shields.io/github/forks/omkarcloud/google-maps-scraper?style=for-the-badge" />
  </a>
  <a href="#">
    <img alt="Repo stars" src="https://img.shields.io/github/stars/omkarcloud/google-maps-scraper?style=for-the-badge&color=yellow" />
  </a>
  <a href="#">
    <img alt="google-maps-scraper License" src="https://img.shields.io/github/license/omkarcloud/google-maps-scraper?color=orange&style=for-the-badge" />
  </a>
  <a href="https://github.com/omkarcloud/google-maps-scraper/issues">
    <img alt="issues" src="https://img.shields.io/github/issues/omkarcloud/google-maps-scraper?color=purple&style=for-the-badge" />
  </a>
</p>
<p align="center">
  <img src="https://views.whatilearened.today/views/github/omkarcloud/google-maps-scraper.svg" width="80px" height="28px" alt="View" />
</p>

<p align="center">
  <a href="https://gitpod.io/#https://github.com/omkarcloud/google-maps-scraper">
    <img alt="Open in Gitpod" src="https://gitpod.io/button/open-in-gitpod.svg" />
  </a>
</p>
  
---

## 👉 Explore Our Other Awesome Products


- ✅ [Botasaurus](https://github.com/omkarcloud/botasaurus): The All-in-One Web Scraping Framework with Anti-Detection, Parallelization, Asynchronous, and Caching Superpowers.

- ✅ [Outlook Account Generator](https://github.com/omkarcloud/outlook-account-generator): Send emails at Google's Scale with Outlook Accounts.


<!-- TODO: UNCOMMENT WHEN DONE -->
<!-- - ✅ [G2 Reviews Scraper](https://github.com/omkarcloud/g2-scraper/): Grow your software's customer base by targeting and converting your competitors' customers. -->

---

⚡ Get 120 Leads in next 5 Minutes! ⚡


I am Google Maps Scraper, created to help you find new customers and grow your sales. 🚀

*Why Scrape Google Maps?* 
Here's why Google Maps is the perfect *hunting ground* for B2B customers:

- 📞 Connect with potential clients directly, drastically reducing the time it takes to seal a deal.

- 🌟 Target rich business owners based on their ```Reviews```, and supercharge your sales.

- 🎯 With access to categories and websites, you can customize your pitch to cater to specific businesses and maximize your sales potential.

Countless entrepreneurs like you have achieved remarkable success by prospecting leads solely from Google Maps, and now it's your turn to make an Impact!

## ⚡ Benefits

Let's delve into some of my remarkable features that you will love:

1. Scrape emails, Facebook, Twitter, and LinkedIn to deliver your message directly to the customer.

2. Limitless Scraping, Say No to costly subscriptions or expensive pay-per-lead fees.

3. Sort, select, and filter leads to find those most relevant to your business.

4. Book resources and strategize on how to reach out to leads effectively.

5. Supports Scraping Thousands of ```Customer Reviews```.

6. Scrape cities across all countries, to make your product reach every corner of the World.

In the next 5 minutes, you'll witness the magic as I extract **120 Leads** from Google Maps for you, opening up a world of opportunities.

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

Ready to skyrocket your customer base? Let's get started! 💼🌍

<!-- ## 🎥 Video Demo

If you'd like to see my powerful capabilities in action before using me, I encourage you to watch this short video.

[![Google Maps Video Tutorial](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/video.png)](https://www.youtube.com/watch?v=6UZhTlkCb9A) -->

## 🚀 Getting Started

Let's get started generating Google Maps Leads by following these super simple steps:

1️⃣ Clone the Magic 🧙‍♀️:
```shell
git clone https://github.com/omkarcloud/google-maps-scraper
cd google-maps-scraper
```
2️⃣ Install Dependencies 📦:
```shell
python -m pip install -r requirements.txt
```
3️⃣ Let the Rain of Google Map Leads Begin 😎:
```shell
python main.py
```

Once the scraping process is complete, you can find your leads in the `output` directory.

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

*Note: If you don't have Python installed or you are facing errors. Follow this Simple FAQ [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it) and you will have your google maps leads in next 5 Minutes*


## 🤔 Questions

### ❓ How to Scrape a Specific Search Query?
Open the `main.py` file, and update the `queries` list with your desired query.

```python
queries = ["web developers in delhi"]
Gmaps.places(queries, max=5)
```

### ❓ How to Scrape Multiple Queries?
Add multiple queries to the `queries` list as follows:

```python
queries = [
   "web developers in bangalore",
   "web developers in delhi",
]
Gmaps.places(queries, max=5)
```

### ❓ The scraper is only retrieving 5 results. How can I scrape all Google Maps search results?
A: Remove the `max` parameter.

By doing so, you can scrape all the Google Maps Listing. For example, to scrape all web developers in Bangalore, modify the code as follows:
```python
queries = ["web developers in bangalore"]
Gmaps.places(queries)
```

You can scrape a maximum of 120 leads per search, as Google does not display any more search results beyond that. However, don't worry about running out of leads as there are thousands of cities in our world :).

### ❓ How Can I Filter Google Map Search Results?
You can apply filters such as:

1. `min_reviews`/`max_reviews` (e.g., 10)
2. `category_in` (e.g., "Dental Clinic", "Dental Laboratory")
3. `has_website` (e.g., True/False)
4. `has_phone` (e.g., True/False)
5. `min_rating`/`max_rating` (e.g., 3.5)

For instance, to scrape listings with at least 5 reviews and no more than 100 reviews, with a phone number but no website:

```python
Gmaps.places(queries, min_reviews=5, max_reviews=100, has_phone=True, has_website=False)
```

To scrape listings that belong to specific categories:

```python
Gmaps.places(queries, category_in=[Gmaps.Category.DentalClinic, Gmaps.Category.DentalLaboratory])
```

See the list of all supported categories [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/categories.md)

### ❓ How to Sort by Reviews, Rating, or Category?
We want you to have the best chance of making a sale by default, so we sort the listings using a really good sorting order, which is as follows:
  - Reviews [Businesses with richer profiles come first]
  - Website [Businesses more open to technology come first]
  - LinkedIn [Businesses that are easier to contact come first]
  - Is Spending On Ads [Businesses already investing in ads are more likely to invest in your product, so they appear first.]

However, you also have the freedom to sort them according to your preferences as follows:

- To sort by reviews:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_REVIEWS_DESCENDING])
  ```

- To sort by rating:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_RATING_DESCENDING])
  ```

- To sort first by reviews and then by those without a website:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_REVIEWS_DESCENDING, Gmaps.SORT_BY_NOT_HAS_WEBSITE])
  ```

- To sort by name (alphabetically):

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_NAME_ASCENDING])
  ```

- To sort by a different field, such as category, in ascending order:

  ```python
  Gmaps.places(queries, sort=[[Gmaps.Fields.CATEGORIES, Gmaps.SORT_ASCENDING]])
  ```

- Or, to sort in descending order:

  ```python
  Gmaps.places(queries, sort=[[Gmaps.Fields.CATEGORIES, Gmaps.SORT_DESCENDING]])
  ```

### ❓ I Need to Reach Out to Leads to Sell My Products/Services. How Do I Scrape Email, Facebook, Twitter, LinkedIn, etc.?

Directly calling potential clients often leads to lower sales success rates, and you may unintentionally come across as fraudulent person.

Instead, use a more effective strategy:
  1. Conduct thorough research on your prospects through their LinkedIn profiles, websites, etc. Then, craft a personalized email. Begin with genuine appreciation for their specific achievements or work, followed by an explanation of how your services can contribute to their business growth.
  2. Send a personalized message to the business owner on LinkedIn.
  3. Reach out via personalized messages on company social media platforms like Twitter and Facebook.

This strategy allows prospects to learn about you before engaging, significantly increasing the likelihood of making a sale.

To scrape contact details of leads, follow these steps to use our Website Social Scraper API with the Free Plan, allowing you to scrape contact details of 50 leads at no cost:

1. Sign up on RapidAPI by visiting [this link](https://rapidapi.com/auth/sign-up).
   
![Sign Up on RapidAPI](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/sign-up.png)

2. Subscribe to the Free Plan by visiting [this link](https://rapidapi.com/Chetan11dev/api/website-social-scraper-api/pricing).

![Subscribe to Free Plan](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/subscribe.png)

3. Copy the API key.
![Copy the API Key](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/key.png)

4. Use it in the scraper as follows:
```python
queries = ["web developers in bangalore"]
Gmaps.places(queries, max=5, key="YOUR_API_KEY") 
```
5. Run the script, and you'll find emails, Facebook, Twitter, and LinkedIn details of leads in your output file.
```bash
python main.py
```   

The first 50 contact details are free. After that, you can upgrade to the Pro Plan to scrape 1,000 contacts for $9, which is affordable considering if you land just one B2B client, you could easily make hundreds of dollars, easily covering the investment.

### ❓ How to scrape all cities in my country?

Consider this example, To scrape web developers from 100 cities in India, use the following example:

```python
queries = Gmaps.Cities.India("web developers in")[0:100]
Gmaps.places(queries) 
```

After running the code, an `india-cities.json` file will be generated in the `output` directory with a list of all the Indian cities.

You can prioritize certain cities by editing the cities JSON file in the output folder and moving them to the top of the list.

We recommend scraping only 100 cities at a time, as countries like India have thousands of cities, and scraping them all could take a considerable amount of time. Once you've exhausted the outreach in 100 cities, you can scrape more.

See the list of all supported countries [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/countries.md)

### ❓ Can I Interrupt the Scrape While It's Running?
Yes, you can. The scraper is smart like you and will resume from where it left off if you interrupt the process.


### ❓ What are popular use cases for entrepreneurs?

- For selling to B2C businesses like restaurants and clothing shops:
  - They should be affluent enough to afford your services.
  - Avoid very large businesses, as they tend to be bureaucratic and harder to sell to.

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries,
             min_reviews=60,
             max_reviews=800,
             key="YOUR_API_KEY")
```

- For selling to B2B businesses like web developers, digital marketers, or less frequent B2C businesses such as dentists, doctors, lawyers:
  - They should be affluent enough to afford your services.

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries, min_reviews=25, key="YOUR_API_KEY") 
```

- For selling web development services to businesses such as restaurants that do not have a website:

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries, min_reviews=25, has_phone=True, has_website=False, key="YOUR_API_KEY") 
```

Most importantly, avoid the temptation to sell to leads with low reviews, as they may not have the budget for your services and could be a time-consuming prospect.

### ❓ How to select more fields?

Seeing a lot of fields can be intimidating, so we have only kept the most important fields in the output.

However, you can select from upto **45+** fields.

Also, To select all the **45+** fields, use the following code:

```python
queries = [
   "web developers in bangalore"
]
Gmaps.places(queries, fields=Gmaps.ALL_FIELDS)
```

To select specific fields only, use the following code:
<!-- todo: use fields -->
```python
queries = [
   "web developers in bangalore"
]

fields = [
   Gmaps.Fields.PLACE_ID, 
   Gmaps.Fields.NAME, 
   Gmaps.Fields.MAIN_CATEGORY, 
   Gmaps.Fields.RATING, 
   Gmaps.Fields.REVIEWS, 
   Gmaps.Fields.WEBSITE, 
   Gmaps.Fields.PHONE, 
   Gmaps.Fields.ADDRESS,
   Gmaps.Fields.LINK, 
]

Gmaps.places(queries, fields=fields)
```

Please note that selecting more or fewer fields will not affect the scraping time; it will remain exactly the same. So, don't fall into the trap of selecting fewer fields thinking it will decrease the scraping time, because it won't. 

For examples of CSV/JSON formats containing all fields, you can download [this file](https://drive.google.com/file/d/10qSpi0Jrh7546M1fakjfBbaAS2ImBr8k/view?usp=sharing).

Also, See the list of all supported fields [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md)

### ❓ Do You Know of an Effective Strategy to Increase the Chances of Selling My Product?

I've personally employed the following strategy to sell my services, which has proven to be highly effective in generating business. By following this approach diligently, I'm confident you can achieve the same successful results that I have experienced.

1. Read [The Cold Email Manifesto](https://www.amazon.com/Cold-Email-Manifesto-pipeline-business-ebook/dp/B0B1DYNNSL) to learn how to write effective cold emails that get responses. 
  - Cold emailing still works in 2023; I say that because I have personally generated $1,000 from sending a personalized cold email to 3-4 contacts at Bright Data (a proxy company), pitching my blog writing services.

2. Draft a compelling cold email template that clearly states your value proposition.

3. Commit to a 21-day goal of reaching out to potential customers. [VERY VERY IMPORTANT]

4. Use the scraper with the contact finding api to gather leads from around 5 cities of your choice, including their emails and social media handles.

5. Send personalized emails to your target businesses and connect with key company personnel on LinkedIn, Facebook, and Twitter.

<!-- **Note:** Avoid cold calling, not because it isn't effective, but because handling rejection over the phone can severely impact your confidence. -->


### ❓ How Does It Work?

For web scrapers interested in understanding how it works, you can read [this tutorial](https://www.omkar.cloud/botasaurus/docs/google-maps-scraping-tutorial/), where we walk you through the creation of a simplified version of a Google Maps Scraper.

### ❓ Your Scraper is really Robust. I Tried Many Scrapers, Most Don't Work. How did you build it?

Thanks! we used Botasaurus, which is the secret sauce behind our Google Maps Scraper.

It's a Web Scraping Framework that makes life easier for Web Scrapers.

Botasaurus handled the hard parts of our Google Maps Scraper, such as:
   - Caching
   - Parallel and Asynchronous Scraping
   - Creation and Reuse of Drivers
   - Writing output to CSV and JSON files
   - And Most importantly, defeating Google's Anti-Scraping Measures


If you are a Web Scraper, we highly recommend that you learn about Botasaurus [here](https://github.com/omkarcloud/botasaurus), because Botasaurus will really save you countless hours in your career as a Web Scraper.

<p align="center">
  <a href="https://github.com/omkarcloud/botasaurus">
  <img src="https://raw.githubusercontent.com/omkarcloud/botasaurus/master/images/mascot.png" alt="botasaurus" />
</a>
</p>

### ❓ Advanced Questions

Having read this page, you have all the knowledge needed to effectively utilize the scraper and ensure a never ending supply of highly relevant leads.

You may choose to explore the following questions based on your interests:

#### For Knowledge

1. [Why Do You Randomize Cities for Each User?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-why-do-you-randomize-cities-for-each-user)
2. [Do I Need Proxies?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-do-i-need-proxies)
3. [Does running Scraper on Bigger Machine scrapes Data Faster?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-does-running-scraper-on-bigger-machine-scrapes-data-faster)

#### For Technical Usage

1. [I don't have Python, or I'm facing errors when setting up the scraper on my PC. How to solve it?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it)
2. [How to Scrape Reviews?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-scrape-reviews)
<!-- 3. [How to select more fields?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-select-more-fields) -->
3. [What are Popular Snippets for Data Scientists?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-what-are-popular-snippets-for-data-scientists)
4. [How to Change the Language of Output?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-change-the-language-of-output)
5. [I have Google Map Places Links, How to Scrape Links?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-have-google-map-places-links-how-to-scrape-links)
6. [How to Scrape at Particular Coordinates and Zoom Level?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-scrape-at-particular-coordinates-and-zoom-level)
7. [When setting the Lang Attribute to Hindi/Japanese/Chinese, the characters are in English instead of the specified language. How to transform characters to the specified language?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-when-setting-the-lang-attribute-to-hindijapanesechinese-the-characters-are-in-english-instead-of-the-specified-language-how-to-transform-characters-to-the-specified-language)

<!-- 4. [How many Keywords Can It Scrape per Hour?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-many-keywords-can-it-scrape-per-hour) -->

### ❓ Need More Help or Have Additional Questions?

For further help, ask your question in GitHub Discussions. We'll be happy to help you out.

[![ask github](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/ask-on-github.png)](https://github.com/omkarcloud/google-maps-scraper/discussions)

## Love It? [Star It ⭐!](https://github.com/omkarcloud/google-maps-scraper)

Become one of our amazing stargazers by giving us a star ⭐ on GitHub!

It's just one click, but it means the world to me.

[![Stargazers for @omkarcloud/google-maps-scraper](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=omkarcloud&repo=google-maps-scraper)](https://github.com/omkarcloud/google-maps-scraper/stargazers)

## Made with ❤️ using [Botasaurus Web Scraping Framework](https://github.com/omkarcloud/botasaurus)

![Google Maps Scraper Feautred Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/google-maps-scraper-feautred-image.png)


<div align="center" style="margin-top: 0;">
  <h1>✨ Google Maps Scraper 🤖</h1>
  <p>💦 Find New Customers and Grow Your Buisness 💦</p>
</div>
<em>
  <h5 align="center">(Programming Language - Python 3)</h5>
</em>
<p align="center">
  <a href="#">
    <img alt="google-maps-scraper forks" src="https://img.shields.io/github/forks/omkarcloud/google-maps-scraper?style=for-the-badge" />
  </a>
  <a href="#">
    <img alt="Repo stars" src="https://img.shields.io/github/stars/omkarcloud/google-maps-scraper?style=for-the-badge&color=yellow" />
  </a>
  <a href="#">
    <img alt="google-maps-scraper License" src="https://img.shields.io/github/license/omkarcloud/google-maps-scraper?color=orange&style=for-the-badge" />
  </a>
  <a href="https://github.com/omkarcloud/google-maps-scraper/issues">
    <img alt="issues" src="https://img.shields.io/github/issues/omkarcloud/google-maps-scraper?color=purple&style=for-the-badge" />
  </a>
</p>
<p align="center">
  <img src="https://views.whatilearened.today/views/github/omkarcloud/google-maps-scraper.svg" width="80px" height="28px" alt="View" />
</p>

<p align="center">
  <a href="https://gitpod.io/#https://github.com/omkarcloud/google-maps-scraper">
    <img alt="Open in Gitpod" src="https://gitpod.io/button/open-in-gitpod.svg" />
  </a>
</p>
  
---

## 👉 Explore Our Other Awesome Products


- ✅ [BOTASAURUS](https://github.com/omkarcloud/botasaurus): The All-in-One Web Scraping Framework with Anti-Detection, Parallelization, Asynchronous, and Caching Superpowers.

- ✅ [GOOGLE SCRAPER](https://github.com/omkarcloud/google-scraper): Discover Search Results from Google.

- ✅ [AMAZON SCRAPER](https://github.com/omkarcloud/amazon-scraper): Discover Search Results and Product Data from Amazon.

- ✅ [TRIP ADVISOR SCRAPER](https://github.com/omkarcloud/tripadvisor-scraper): Discover websites, emails, and phone numbers of hotels and restaurants from the untapped gold mine of TripAdvisor leads.

<!-- TODO: UNCOMMENT WHEN DONE -->
<!-- - ✅ [G2 Reviews Scraper](https://github.com/omkarcloud/g2-scraper/): Grow your software's customer base by targeting and converting your competitors' customers. -->

---

⚡ Get 120 Leads in next 5 Minutes! ⚡


I am Google Maps Scraper, created to help you find new customers and grow your sales. 🚀

*Why Scrape Google Maps?* 
Here's why Google Maps is the perfect *hunting ground* for B2B customers:

- 📞 Connect with potential clients directly, drastically reducing the time it takes to seal a deal.

- 🌟 Target rich business owners based on their ```Reviews```, and supercharge your sales.

- 🎯 With access to categories and websites, you can customize your pitch to cater to specific businesses and maximize your sales potential.

Countless entrepreneurs like you have achieved remarkable success by prospecting leads solely from Google Maps, and now it's your turn to make an Impact!

## ⚡ Benefits

Let's delve into some of my remarkable features that you will love:

1. Scrape emails, Facebook, Twitter, and LinkedIn to deliver your message directly to the customer.

2. Limitless Scraping, Say No to costly subscriptions or expensive pay-per-lead fees.

3. Sort, select, and filter leads to find those most relevant to your business.

4. Book resources and strategize on how to reach out to leads effectively.

5. Supports Scraping Thousands of ```Customer Reviews```.

6. Scrape cities across all countries, to make your product reach every corner of the World.

In the next 5 minutes, you'll witness the magic as I extract **120 Leads** from Google Maps for you, opening up a world of opportunities.

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

Ready to skyrocket your customer base? Let's get started! 💼🌍

## 🎥 Video Demo

If you'd like to see my powerful capabilities in action before using me, I encourage you to watch this short video.

[![Google Maps Video Tutorial](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/video.png)](https://www.youtube.com/watch?v=6UZhTlkCb9A)


## 📦 Requirements

To use the scraper, you must have Node.js 18+ and Python 3.8+ installed on your PC.

## 🚀 Getting Started

Let's get started generating Google Maps Leads by following these super simple steps:

1️⃣ Clone the Magic 🧙‍♀️:
```shell
git clone https://github.com/omkarcloud/google-maps-scraper
cd google-maps-scraper
```
2️⃣ Install Dependencies 📦:
```shell
python -m pip install -r requirements.txt
```
3️⃣ Let the Rain of Google Map Leads Begin 😎:
```shell
python main.py
```

Once the scraping process is complete, you can find your leads in the `output` directory.

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

*Note: If you don't have Nodejs and Python installed or you are facing errors. Follow this Simple FAQ [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it) and you will have your google maps leads in next 5 Minutes*


## 🤔 Questions

### ❓ How to Scrape a Specific Search Query?
Open the `main.py` file, and update the `queries` list with your desired query.

```python
queries = ["web developers in delhi"]
Gmaps.places(queries, max=5)
```

### ❓ How to Scrape Multiple Queries?
Add multiple queries to the `queries` list as follows:

```python
queries = [
   "web developers in bangalore",
   "web developers in delhi",
]
Gmaps.places(queries, max=5)
```

### ❓ The scraper is only retrieving 5 results. How can I scrape all Google Maps search results?
A: Remove the `max` parameter.

By doing so, you can scrape all the Google Maps Listing. For example, to scrape all web developers in Bangalore, modify the code as follows:
```python
queries = ["web developers in bangalore"]
Gmaps.places(queries)
```

You can scrape a maximum of 120 leads per search, as Google does not display any more search results beyond that. However, don't worry about running out of leads as there are thousands of cities in our world :).

### ❓ How Can I Filter Google Map Search Results?
You can apply filters such as:

1. `min_reviews`/`max_reviews` (e.g., 10)
2. `category_in` (e.g., "Dental Clinic", "Dental Laboratory")
3. `has_website` (e.g., True/False)
4. `has_phone` (e.g., True/False)
5. `min_rating`/`max_rating` (e.g., 3.5)

For instance, to scrape listings with at least 5 reviews and no more than 100 reviews, with a phone number but no website:

```python
Gmaps.places(queries, min_reviews=5, max_reviews=100, has_phone=True, has_website=False)
```

To scrape listings that belong to specific categories:

```python
Gmaps.places(queries, category_in=[Gmaps.Category.DentalClinic, Gmaps.Category.DentalLaboratory])
```

See the list of all supported categories [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/categories.md)

### ❓ How to Sort by Reviews, Rating, or Category?
We want you to have the best chance of making a sale by default, so we sort the listings using a really good sorting order, which is as follows:
  - Reviews [Businesses with richer profiles come first]
  - Website [Businesses more open to technology come first]
  - LinkedIn [Businesses that are easier to contact come first]
  - Is Spending On Ads [Businesses already investing in ads are more likely to invest in your product, so they appear first.]

However, you also have the freedom to sort them according to your preferences as follows:

- To sort by reviews:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_REVIEWS_DESCENDING])
  ```

- To sort by rating:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_RATING_DESCENDING])
  ```

- To sort first by reviews and then by those without a website:

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_REVIEWS_DESCENDING, Gmaps.SORT_BY_NOT_HAS_WEBSITE])
  ```

- To sort by name (alphabetically):

  ```python
  Gmaps.places(queries, sort=[Gmaps.SORT_BY_NAME_ASCENDING])
  ```

- To sort by a different field, such as category, in ascending order:

  ```python
  Gmaps.places(queries, sort=[[Gmaps.Fields.CATEGORIES, Gmaps.SORT_ASCENDING]])
  ```

- Or, to sort in descending order:

  ```python
  Gmaps.places(queries, sort=[[Gmaps.Fields.CATEGORIES, Gmaps.SORT_DESCENDING]])
  ```


### ❓ How to Scrape Additional Information like Website, Phone, Geo Coordinates, Price Range?

You may upgrade to the Pro Version of the Google Maps Scraper to scrape additional data points, like:

- 🌐 **Website**
- 📞 **Phone Numbers**
- 🌍 **Geo Coordinates**
- 💰 **Price Range**
- And **45+ data points** like Owner details, Photos, About Section, and [many more](https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md)!

Below is a sample lead scraped by the Pro Version:

![Pro Lead](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/paid-lead.png)

*View sample leads scraped by the Pro Version [here](https://drive.google.com/file/d/10qSpi0Jrh7546M1fakjfBbaAS2ImBr8k/view?usp=sharing)*

Also, See the list of fields scraped by Pro Version [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md)

🔍 **Comparison**:

See how the Pro Version stacks up against the free version in this comparison image:

![Comparison Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/comparision-image.png)

And here's the best part - the Pro Version offers great ROI because it helps you land new customers bringing hundreds and thousands of dollars, all with zero risk. That's right because, we offer a **30-Day Refund Policy**!


### ❓ How to Get the Pro Version?

Visit the Sponsorship Page [here](https://github.com/sponsors/omkarcloud?frequency=one-time) and pay $28 by selecting Google Maps Scraper Pro Option.

![Pay](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/pay.gif)

After payment, you'll see a success screen with instructions on how to use the Pro Version:

![Success Screen](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/success-screen.png)

### ❓What if I Don't Get Value from It?

We wholeheartedly believe in the value our product brings, especially since it has successfully worked for hundreds of entrepreneurs like you.
 
But, we also understand the reservations you might have.

That's why we've put the ball in your court: If, within the next 30 days, you feel that our product hasn’t met your expectations, don't hesitate. Reach out to us, and We will gladly refund your money, no questions and no hassles.

The risk is entirely on us because we're confident in what we've created.

### ❓ How Do I Get a Refund?

Requesting a refund is a simple process that should only take about 5 minutes. To request a refund, ensure you have one of the following:

- **A PayPal Account (e.g., "myname@example.com" or "chetan@gmail.com")**
- **or a UPI ID (India only) (e.g., 'myname@bankname" or "chetan@okhdfc")**

Next, follow these steps to initiate a refund:

1. Send an email to `chetan@omkar.cloud` using the following template:

   - To request a refund via PayPal:
     ```
     Subject: Request Refund
     Content: Please send a refund to my PayPal email: myname@example.com
     ```

   - To request a refund via UPI (India Only):
     ```
     Subject: Request Refund
     Content: Please send a refund to my UPI ID: myname@bankname
     ```

   ![Email Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/email.png)

2. Next, go to the discussion [here](https://github.com/omkarcloud/google-maps-scraper/discussions/44) and comment to request a refund using this template:
   ```
   I have sent a refund request from my email: myname@example.com.
   ```

   ![Discussion Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/discussion.png)

3. You can expect to receive your refund within 1 day. We will also update you in the GitHub Discussion [here](https://github.com/omkarcloud/google-maps-scraper/discussions/44) :)

   ![PayPal Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/paypal.png)


### ❓ I Need to Reach Out to Leads to Sell My Products/Services. How Do I Scrape Email, Facebook, Twitter, LinkedIn, etc.?

Directly calling potential clients often leads to lower sales success rates, and you may unintentionally come across as fraudulent person.

Instead, use a more effective strategy:
  1. Conduct thorough research on your prospects through their LinkedIn profiles, websites, etc. Then, craft a personalized email. Begin with genuine appreciation for their specific achievements or work, followed by an explanation of how your services can contribute to their business growth.
  2. Send a personalized message to the business owner on LinkedIn.
  3. Reach out via personalized messages on company social media platforms like Twitter and Facebook.

This strategy allows prospects to learn about you before engaging, significantly increasing the likelihood of making a sale.

To scrape contact details of leads, follow these steps to use our Website Social Scraper API with the Free Plan, allowing you to scrape contact details of 50 leads at no cost:

1. Sign up on RapidAPI by visiting [this link](https://rapidapi.com/auth/sign-up).
   
![Sign Up on RapidAPI](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/sign-up.png)

2. Subscribe to the Free Plan by visiting [this link](https://rapidapi.com/Chetan11dev/api/website-social-scraper-api/pricing).

![Subscribe to Free Plan](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/subscribe.png)

3. Copy the API key.
![Copy the API Key](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/key.png)

4. Use it in the scraper as follows:
```python
queries = ["web developers in bangalore"]
Gmaps.places(queries, max=5, key="YOUR_API_KEY") 
```
5. Run the script, and you'll find emails, Facebook, Twitter, and LinkedIn details of leads in your output file.
```bash
python main.py
```   

The first 50 contact details are free. After that, you can upgrade to the Pro Plan to scrape 1,000 contacts for $9, which is affordable considering if you land just one B2B client, you could easily make hundreds of dollars, easily covering the investment.

### ❓ How to scrape all cities in my country?

Consider this example, To scrape web developers from 100 cities in India, use the following example:

```python
queries = Gmaps.Cities.India("web developers in")[0:100]
Gmaps.places(queries) 
```

After running the code, an `india-cities.json` file will be generated in the `output` directory with a list of all the Indian cities.

You can prioritize certain cities by editing the cities JSON file in the output folder and moving them to the top of the list.

We recommend scraping only 100 cities at a time, as countries like India have thousands of cities, and scraping them all could take a considerable amount of time. Once you've exhausted the outreach in 100 cities, you can scrape more.

See the list of all supported countries [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/countries.md)

### ❓ Can I Interrupt the Scrape While It's Running?
Yes, you can. The scraper is smart like you and will resume from where it left off if you interrupt the process.


### ❓ What are popular use cases for entrepreneurs?

- For selling to B2C businesses like restaurants and clothing shops:
  - They should be affluent enough to afford your services.
  - Avoid very large businesses, as they tend to be bureaucratic and harder to sell to.

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries,
             min_reviews=60,
             max_reviews=800,
             key="YOUR_API_KEY")
```

- For selling to B2B businesses like web developers, digital marketers, or less frequent B2C businesses such as dentists, doctors, lawyers:
  - They should be affluent enough to afford your services.

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries, min_reviews=25, key="YOUR_API_KEY") 
```

- For selling web development services to businesses such as restaurants that do not have a website:

```python
queries = Gmaps.Cities.India("your_target_customer in")[0:5]
Gmaps.places(queries, min_reviews=25, has_phone=True, has_website=False, key="YOUR_API_KEY") 
```

Most importantly, avoid the temptation to sell to leads with low reviews, as they may not have the budget for your services and could be a time-consuming prospect.

### ❓ How to select more fields? [For Pro Users Only]

Seeing a lot of fields can be intimidating, so we have only kept the most important fields in the output.

However, you can select from upto **45+** fields.

Also, To select all the **45+** fields, use the following code:

```python
queries = [
   "web developers in bangalore"
]
Gmaps.places(queries, fields=Gmaps.ALL_FIELDS)
```

To select specific fields only, use the following code:
<!-- todo: use fields -->
```python
queries = [
   "web developers in bangalore"
]

fields = [
   Gmaps.Fields.PLACE_ID, 
   Gmaps.Fields.NAME, 
   Gmaps.Fields.MAIN_CATEGORY, 
   Gmaps.Fields.RATING, 
   Gmaps.Fields.REVIEWS, 
   Gmaps.Fields.WEBSITE, 
   Gmaps.Fields.PHONE, 
   Gmaps.Fields.ADDRESS,
   Gmaps.Fields.LINK, 
]

Gmaps.places(queries, fields=fields)
```

Please note that selecting more or fewer fields will not affect the scraping time; it will remain exactly the same. So, don't fall into the trap of selecting fewer fields thinking it will decrease the scraping time, because it won't. 

For examples of CSV/JSON formats containing all fields, you can download [this file](https://drive.google.com/file/d/10qSpi0Jrh7546M1fakjfBbaAS2ImBr8k/view?usp=sharing).

Also, See the list of all supported fields [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md)

### ❓ Do You Know of an Effective Strategy to Increase the Chances of Selling My Product?

I've personally employed the following strategy to sell my services, which has proven to be highly effective in generating business. By following this approach diligently, I'm confident you can achieve the same successful results that I have experienced.

1. Read [The Cold Email Manifesto](https://www.amazon.com/Cold-Email-Manifesto-pipeline-business-ebook/dp/B0B1DYNNSL) to learn how to write effective cold emails that get responses. 
  - Cold emailing still works in 2023; I say that because I have personally generated $1,000 from sending a personalized cold email to 3-4 contacts at Bright Data (a proxy company), pitching my blog writing services.

2. Draft a compelling cold email template that clearly states your value proposition.

3. Commit to a 21-day goal of reaching out to potential customers. [VERY VERY IMPORTANT]

4. Use the scraper with the contact finding api to gather leads from around 5 cities of your choice, including their emails and social media handles.

5. Send personalized emails to your target businesses and connect with key company personnel on LinkedIn, Facebook, and Twitter.

<!-- **Note:** Avoid cold calling, not because it isn't effective, but because handling rejection over the phone can severely impact your confidence. -->

### ❓ Are There Other Sources of Great Leads that I can use?

Google Maps is heavily scraped, the competition for these leads is intense. Many of them might already have been contacted by your competition.

Therefore, we suggest adopting a different approach: scrape leads from platforms like TripAdvisor. Leads from TripAdvisor are far less scraped compared to Google Maps, allowing you to access leads that your competition hasn't yet contacted, potentially leading to much higher closing rates.

Also, if hotel and restaurant owners are your primary target audience, consider using TripAdvisor Leads instead of Google Maps Leads due to the lower competition.

Our TripAdvisor Scraper allows you to easily gather contact information such as emails, phone numbers, and websites from TripAdvisor. 

Discover leads with less competition and grow your sales by checking out our [Tripadvisor Scraper here](https://github.com/omkarcloud/tripadvisor-scraper)


### ❓ How Does It Work?

For web scrapers interested in understanding how it works, you can read [this tutorial](https://www.omkar.cloud/botasaurus/docs/google-maps-scraping-tutorial/), where we walk you through the creation of a simplified version of a Google Maps Scraper.

### ❓ Your Scraper is really Robust. I Tried Many Scrapers, Most Don't Work. How did you build it?

Thanks! we used Botasaurus, which is the secret sauce behind our Google Maps Scraper.

It's a Web Scraping Framework that makes life easier for Web Scrapers.

Botasaurus handled the hard parts of our Google Maps Scraper, such as:
   - Caching
   - Parallel and Asynchronous Scraping
   - Creation and Reuse of Drivers
   - Writing output to CSV and JSON files
   - And Most importantly, defeating Google's Anti-Scraping Measures


If you are a Web Scraper, we highly recommend that you learn about Botasaurus [here](https://github.com/omkarcloud/botasaurus), because Botasaurus will really save you countless hours in your career as a Web Scraper.

<p align="center">
  <a href="https://github.com/omkarcloud/botasaurus">
  <img src="https://raw.githubusercontent.com/omkarcloud/botasaurus/master/images/mascot.png" alt="botasaurus" />
</a>
</p>

### ❓ Advanced Questions

Having read this page, you have all the knowledge needed to effectively utilize the scraper and ensure a never ending supply of highly relevant leads.

You may choose to explore the following questions based on your interests:

#### For Knowledge

1. [Why Do You Randomize Cities for Each User?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-why-do-you-randomize-cities-for-each-user)
2. [Do I Need Proxies?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-do-i-need-proxies)
3. [Does running Scraper on Bigger Machine scrapes Data Faster?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-does-running-scraper-on-bigger-machine-scrapes-data-faster)

#### For Technical Usage

1. [I don't have Python, or I'm facing errors when setting up the scraper on my PC. How to solve it?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it)
2. [How to Scrape Reviews?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-scrape-reviews)
<!-- 3. [How to select more fields?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-select-more-fields) -->
3. [What are Popular Snippets for Data Scientists?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-what-are-popular-snippets-for-data-scientists)
4. [How to Change the Language of Output?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-change-the-language-of-output)
5. [I have Google Map Places Links, How to Scrape Links?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-have-google-map-places-links-how-to-scrape-links)
6. [How to Scrape at Particular Coordinates and Zoom Level?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-to-scrape-at-particular-coordinates-and-zoom-level)
7. [When setting the Lang Attribute to Hindi/Japanese/Chinese, the characters are in English instead of the specified language. How to transform characters to the specified language?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-when-setting-the-lang-attribute-to-hindijapanesechinese-the-characters-are-in-english-instead-of-the-specified-language-how-to-transform-characters-to-the-specified-language)

<!-- 4. [How many Keywords Can It Scrape per Hour?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-how-many-keywords-can-it-scrape-per-hour) -->

### ❓ Need More Help or Have Additional Questions?

For further help, contact us on WhatsApp. We'll be happy to help you out.

[![Contact Us on WhatsApp about Amazon Scraper](https://raw.githubusercontent.com/omkarcloud/assets/master/images/whatsapp-us.png)](https://api.whatsapp.com/send?phone=918295042963&text=Hi,%20I%20would%20like%20to%20learn%20more%20about%20your%20products.)

## Love It? [Star It ⭐!](https://github.com/omkarcloud/google-maps-scraper)

Become one of our amazing stargazers by giving us a star ⭐ on GitHub!

It's just one click, but it means the world to me.

[![Stargazers for @omkarcloud/google-maps-scraper](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=omkarcloud&repo=google-maps-scraper)](https://github.com/omkarcloud/google-maps-scraper/stargazers)

## Made with ❤️ using [Botasaurus Web Scraping Framework](https://github.com/omkarcloud/botasaurus)

![Google Maps Scraper Feautred Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/google-maps-scraper-feautred-image.png)

<div align="center" style="margin-top: 0;">
  <h1>✨ Google Maps Scraper 🤖</h1>
</div>
<em>
  <h5 align="center">(Programming Language - Python 3)</h5>
</em>
<p align="center">
  <a href="#">
    <img alt="google-maps-scraper forks" src="https://img.shields.io/github/forks/omkarcloud/google-maps-scraper?style=for-the-badge" />
  </a>
  <a href="#">
    <img alt="Repo stars" src="https://img.shields.io/github/stars/omkarcloud/google-maps-scraper?style=for-the-badge&color=yellow" />
  </a>
  <a href="#">
    <img alt="google-maps-scraper License" src="https://img.shields.io/github/license/omkarcloud/google-maps-scraper?color=orange&style=for-the-badge" />
  </a>
  <a href="https://github.com/omkarcloud/google-maps-scraper/issues">
    <img alt="issues" src="https://img.shields.io/github/issues/omkarcloud/google-maps-scraper?color=purple&style=for-the-badge" />
  </a>
</p>
<p align="center">
  <img src="https://views.whatilearened.today/views/github/omkarcloud/google-maps-scraper.svg" width="80px" height="28px" alt="View" />
</p>

<p align="center">
  <a href="https://gitpod.io/#https://github.com/omkarcloud/google-maps-scraper">
    <img alt="Open in Gitpod" src="https://gitpod.io/button/open-in-gitpod.svg" />
  </a>
</p>
  
---

## Disclaimer for Google Maps Scraper Project

> This Google Maps Scraper is provided for educational and research purposes only. By using this Google Maps Scraper, you agree to comply with local and international laws regarding data scraping and privacy. The authors and contributors are not responsible for any misuse of this software. This tool should not be used to violate the rights of others, for unethical purposes, or to use data in an unauthorized or illegal manner.

We take the concerns of the Google Maps Scraper Project very seriously. For any concerns, please contact Chetan Jain at [chetan@omkar.cloud](mailto:chetan@omkar.cloud). We will promptly reply to your emails.

##  Explore Our Other Awesome Products

- ✅ [BOTASAURUS](https://github.com/omkarcloud/botasaurus): The All-in-One Web Scraping Framework with Anti-Detection, Parallelization, Asynchronous, and Caching Superpowers.

<!-- - ✅ [GOOGLE SCRAPER](https://github.com/omkarcloud/google-scraper): Discover Search Results from Google. -->

<!-- - ✅ [AMAZON SCRAPER](https://github.com/omkarcloud/amazon-scraper): Discover Search Results and Product Data from Amazon. -->

<!-- - ✅ [TRIP ADVISOR SCRAPER](https://github.com/omkarcloud/tripadvisor-scraper): Discover search results of hotels and restaurants from TripAdvisor. -->

---

Google Maps Scraper helps you find Business Profiles from Google Maps.

## ⚡ Benefits

1. Easy-to-use, friendly dashboard.

2. Limitless scraping: Say sayonara to costly subscriptions or expensive pay-per-result fees.

3. Highly scalable, capable of running on Kubernetes, Docker, and servers.

4. Scrape data for a specific type of business across all cities in a country.

5. Get the exact results you need by easily sorting, filtering, and exporting data as CSV, Excel, or JSON files.

6. Scrape reviews while ensuring the privacy of reviewers is maintained.

In the next 5 minutes, you'll extract **120 Search Results** from Google Maps.

![Google Maps Data Scraper CSV Result](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/gmap_result.png)

## 📦 Requirements

To use this tool, you'll need:

- Node.js version 16 or later to run the UI Dashboard (please check your Node.js version by running `node -v`)
- Python for running the scraper

**Don't have Node.js or Python? No problem!**  

You can easily run this tool within Gitpod, a cloud-based development environment. We'll cover how to set that up later. 

## 🚀 Getting Started

Let's get started by following these super simple steps:

1️⃣ Clone the Magic 🧙‍♀️:
```shell
git clone https://github.com/omkarcloud/google-maps-scraper
cd google-maps-scraper
```

2️⃣ Install Dependencies 📦:
```shell
python -m pip install -r requirements.txt && python run.py install
```

3️⃣ Launch the UI Dashboard 🚀:
```shell
python run.py
```

4️⃣ Open your browser and go to [http://localhost:3000](http://localhost:3000), then press the Run button to have 120 search results within 2 minutes. 😎

![GIF of Google Maps Scraper Visit, Highlish Keyword, Run, See Results](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/demo.gif)

*Note: If you don't have Node.js 16+ and Python installed or you are facing errors, follow this Simple FAQ [here](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it), and you will have your search results in the next 5 Minutes*

## ⚡ Enlightening Questions

### ❓ How to Get Results for My Queries?

1. Visit [http://localhost:3000](http://localhost:3000) and enter your search queries.

![Queries](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/queries.png)

2. Now, simply press the Run button.

![Run](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/run.png)

### ❓ What are the different pages and how do they help me?

Primarily, there are 3 pages in the UI Dashboard:

- Home Page ('/')
- Output Page ('/output')
- Results Page ('/output/1')

#### Home Page ('/')

![Homepage](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/homepage.png)

You can input your queries here and search by:
- List of queries
![Queries](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/queries.png)

- List of links
![links-queries](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/links-queries.png)

- Scrape data for a specific type of business across all cities in a country.
![country-section](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/country-section.png)

- Get Social Details of Profiles like Email, LinkedIn, Facebook, Twitter, etc.
![social-section.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/social-section.png)

Extracting social details is a compute-intensive process that involves searching various directories and websites parallelly using proxies. To help with this process, we've created an API.

Kindly follow these steps to use the API and get the social details of the profiles:

1. Sign up on RapidAPI by visiting [this link](https://rapidapi.com/auth/sign-up).

![Sign Up on RapidAPI](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/sign-up.png)

2. Subscribe to the Free Plan by visiting [this link](https://rapidapi.com/Chetan11dev/api/website-social-scraper-api/pricing).

![Subscribe to Free Plan](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/subscribe.png)

3. Copy the API key.
![Copy the API Key](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/key.png)

4. Put the Key in the "Email and Social Links Extraction" section and run it:

![social-section.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/social-section.png)

The first 200 contact details are free to scrape with the API. After that, you can upgrade to the Pro Plan to scrape 1,000 contacts for $9, which is affordable considering if you land just one customer, you could easily make hundreds of dollars, easily covering the investment.

- Scrape Reviews
![reviews-section](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/reviews-section.png)

Kindly note that due to privacy concerns, we do not scrape personally identifiable information of reviewers, such as names, profile photos, and review links. We only scrape the review text, rating, owner response, and similar non-personally identifiable information.

#### Output Page ('/output')
![output-page.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/output-page.png)

The Output page helps you manage your tasks. You can use it to:

- See tasks and their status (pending, in progress, or completed).
- Abort or delete any task.
![abort-delete.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/abort-delete.png)

- Additionally, Whenever you run a query, a task named "All Task" will be created for it, which combines results from multiple queries.

For example, if you search for "Web Developers in Bangalore" and "Web Developers in Mumbai", the "All Task" will show you the combined results for both queries.

![all-task.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/all-task.png)

#### Results Page ('/output/1')
![results-page.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/results-page.png)

This is the most important page where you can view, sort, filter, or download the results of the task.

**Sorting**

![sort.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/sort.png)

By default, we sort the listings using a really good sorting order, which is as follows ("Best Potential Customers"):

- Reviews [Businesses with more reviews come first]
- Website [Businesses more open to technology come first]
- Is Spending On Ads [Businesses already investing in ads are more likely to invest in your product, so they appear first.]

You can also sort by other criteria, such as name or reviews.

![sort-small.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/sort-small.png)

**Filters**

![filter.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/filter.png)

To find the exact results you're looking for, click the "Show Filters" button and apply the desired filters.

**Export**

![export.png](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/export.png)

Download results in various formats (CSV, JSON, Excel) using the export button.

### ❓ How can I access additional information like websites, phone numbers, geo-coordinates, and price ranges?

Free versions shows only a limited set of data points. To see additional datapoints, consider upgrading to the Pro Version:

* 🌐 **Website**
* 📞 **Phone Numbers**
* 🌍 **Geo-Coordinates**
* 💰 **Price Range**
* **And many more!** Explore a full list of data points here: [https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md](https://github.com/omkarcloud/google-maps-scraper/blob/master/fields.md)

The Pro Version is a one-time investment with lifetime updates and absolutely zero risk because we offer a generous **90-Day Refund Policy!**


### ❓ How to Get the Pro Version?

Visit the GitHub Sponsorship Page [here](https://github.com/sponsors/omkarcloud?frequency=one-time) and make a one time payment of $28 by selecting Google Maps Scraper Pro Option.

![Pay](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/pay.gif)

After payment, you'll see a success screen with instructions on how to use the Pro Version:

![Success Screen](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/success-screen.png)

### ❓ What if I Don't Get Value from It?

We wholeheartedly ❤️ believe in the value our product brings for you, especially since it has successfully worked for hundreds of people like you.
 
But, we also understand the reservations you might have.

That's why we've put the ball in your court: **If, within the next 90 days, you feel that our product hasn’t met your expectations, don't hesitate. Reach out to us, and within 24 hours, we will gladly refund your money, no questions and no hassles.**

The risk is entirely on us! because we're that confident in what we've created!

### ❓ How Do I Get a Refund?

We are ethical and honest people, and we will not keep your money if you are not happy with our product. Requesting a refund is a simple process that should only take about 5 minutes. To request a refund, ensure you have one of the following:

- **A PayPal Account (e.g., "myname@example.com" or "chetan@gmail.com")**
- **or a UPI ID (For India Only) (e.g., 'myname@bankname' or 'chetan@okhdfc')**

Next, follow these steps to initiate a refund:

1. Send an email to `chetan@omkar.cloud` using the following template:

   - To request a refund via PayPal:
     ```
     Subject: Request Refund
     Content: Please send a refund to my PayPal email: myname@example.com
     ```

   - To request a refund via UPI (For India Only):
     ```
     Subject: Request Refund
     Content: Please send a refund to my UPI ID: myname@bankname
     ```

   ![Email Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/email.png)

2. Next, go to the discussion [here](https://github.com/omkarcloud/google-maps-scraper/discussions/44) and comment to request a refund using this template:
   ```
   I have sent a refund request from my email: myname@example.com.
   ```

   ![Discussion Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/discussion.png)

3. You can expect to receive your refund within 1 day. We will also update you in the GitHub Discussion [here](https://github.com/omkarcloud/google-maps-scraper/discussions/44) :)

   ![PayPal Image](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/paypal.png)

Also, the Complete $28 will be refunded to you within 24 hours, without any questions and without any hidden charges.

### ❓ Could you share resources that would be helpful to me, as I am sending personalized emails providing people with useful services?

I recommend reading [The Cold Email Manifesto](https://www.amazon.com/Cold-Email-Manifesto-pipeline-business-ebook/dp/B0B1DYNNSL) by Alex Berman to learn how to emails that get replies. 

Rest assured, I have your interest at my heart, and the above link is not an affiliate link. It's just a really awesome book, that's why I'm recommending it to you.
### ❓ This Scraper is Truly One-of-a-Kind, Something I've Never Seen Before. How Did You Build It?

Thank you! We used Botasaurus, which is the secret behind our awesome Google Maps Scraper.

Botasaurus is a web scraping framework that makes life a lot easier for web scrapers.

It handled the hardest parts of our scraper, such as:

- Creating a gorgeous UI dashboard with task management features
- Sorting, filtering, and exporting data as CSV, JSON, Excel, etc.
- Caching, parallel and asynchronous scraping, and anti-detection measures
- Built-in integration with Kubernetes, Docker, Server, Gitpod, and a REST API

If you're a web scraper, I really recommend learning about Botasaurus [here 🚀](https://github.com/omkarcloud/botasaurus).

Trust me, learning Botasaurus will only take 20 minutes, but I guarantee it will definitely save you thousands of hours in your life as a web scraper.

<p align="center">
  <a href="https://github.com/omkarcloud/botasaurus">
    <img src="https://raw.githubusercontent.com/omkarcloud/botasaurus/master/images/mascot.png" alt="botasaurus" />
  </a>
</p>

### ❓ Advanced Questions

Having read this page, you have all the knowledge needed to effectively use the tool.

You may choose to read the following questions based on your interests:

1. [I Don't Have Python, or I'm Facing Errors When Setting Up the Scraper on My PC. How to Solve It?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-i-dont-have-python-or-im-facing-errors-when-setting-up-the-scraper-on-my-pc-how-to-solve-it)
2. [Do I Need Proxies?](https://github.com/omkarcloud/google-maps-scraper/blob/master/advanced.md#-do-i-need-proxies)

### ❓ Need More Help or Have Additional Questions?

For further help, feel free to reach out to us through:

- **WhatsApp:** If you prefer WhatsApp, simply send a message [here](https://api.whatsapp.com/send?phone=918295042963&text=Hi,%20I%20would%20like%20to%20learn%20more%20about%20your%20products). Also, to help me provide the best possible answer, please include as much detail as possible.

  [![Contact Us on WhatsApp about Google Maps Scraper](https://raw.githubusercontent.com/omkarcloud/assets/master/images/whatsapp-us.png)](https://api.whatsapp.com/send?phone=918295042963&text=Hi,%20I%20would%20like%20to%20learn%20more%20about%20your%20products)


- **GitHub Discussions:** If you believe your question could benefit the community, feel free to post it in our GitHub discussions [here](https://github.com/omkarcloud/google-maps-scraper/discussions).

  [![Contact Us on GitHub Discussion](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/ask-on-github.png)](https://github.com/omkarcloud/google-maps-scraper/discussions)

- **Email:** If you prefer email, kindly send your queries to [chetan@omkar.cloud](mailto:chetan@omkar.cloud). Also, to help me provide the best possible answer, please include as much detail as possible.

  [![Contact Us on Email about Google Maps Scraper](https://raw.githubusercontent.com/omkarcloud/google-maps-scraper/master/screenshots/ask-on-email.png)](mailto:chetan@omkar.cloud)

We look forward to helping you and will respond to emails and whatsapp messages within 24 hours.

Good Luck!

## Love It? [Star It ⭐!](https://github.com/omkarcloud/google-maps-scraper)

Become one of our amazing stargazers by giving us a star ⭐ on GitHub!

It's just one click, but it means the world to me.

[![Stargazers for @omkarcloud/google-maps-scraper](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=omkarcloud&repo=google-maps-scraper)](https://github.com/omkarcloud/google-maps-scraper/stargazers)

## Made with ❤️ using [Botasaurus Web Scraping Framework](https://github.com/omkarcloud/botasaurus)
