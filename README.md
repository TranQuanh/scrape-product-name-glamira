# GLAMIRA WEBSITE CRAWLING PROJECT


 ![image](https://scamminder.com/include/uploads/2024/06/glamira.pt.png)


# :books: Table of Contents <!-- omit in toc -->

- [:briefcase: Business Case and Requirement](#briefcase-business-case-and-requirement)
- [:bookmark_tabs:Example Product Dictionary](#bookmark_tabsexample-product-dictionay)


- [📃 What can you practice with this case study?](#what-can-you-practice-with-this-case-study)

---

# :briefcase: Business Case and Requirement


As a Data Engineer working for an AI company, your task is to design and implement an efficient web crawling bot to gather product photos along with their descriptions and information on website [www.glamira.com](www.glamira.com) for the purpose of training a machine learning model for jewelry product detection. Here are the key requirements:

### 1. Efficient Crawling Bot:

Develop a web crawler that can efficiently and accurately extract product photos, descriptions, and other relevant information from targeted websites.
Ensure the crawler adheres to the websites' robots.txt rules and terms of service.
Implement mechanisms to handle dynamic content, pagination, and possible anti-crawling measures.
Optimize the crawler for speed and low resource consumption.
Product Information Dictionary:

### 2.Create a well-structured dictionary to store the crawled data.
The dictionary should include keys for storing product IDs, names, descriptions, image URLs, prices, categories, and any other relevant information.
Ensure the dictionary format is consistent and easily convertible to a structured data format like JSON or CSV for further processing.

---

# :bookmark_tabs:Example Product Dictionay

```python
"GLAMIRA Earring Gaisma - B": {
        "14K Yellow Gold & Emerald": {
            "Product Name": "GLAMIRA Earring Gaisma - B",
            "Product ID": "159474",
            "Product Full Link": "https://www.glamira.com/glamira-earring-gaisma-b.html?alloy=yellow-585&stone1=emerald",
            "Category ID": "1039",
            "Price": "$379.00",
            "Carat": "0.06 crt  - AAA",
            "Detail": {
                "alloy": "yellow-585",
                "stone1": "emerald"
            },
            "Descript": "14K Yellow Gold & Emerald",
            "Product Image Path": [
                "D:\\VScode\\DE\\crawl_data\\Beautifulsoup\\Glamira\\project_glamira\\photo\\image_159474_GLAMIRA-Earring-Gaisma---B_alloy=yellow-585&stone1=emerald_1",
                "D:\\VScode\\DE\\crawl_data\\Beautifulsoup\\Glamira\\project_glamira\\photo\\image_159474_GLAMIRA-Earring-Gaisma---B_alloy=yellow-585&stone1=emerald_2",
                "D:\\VScode\\DE\\crawl_data\\Beautifulsoup\\Glamira\\project_glamira\\photo\\image_159474_GLAMIRA-Earring-Gaisma---B_alloy=yellow-585&stone1=emerald_3",
                "D:\\VScode\\DE\\crawl_data\\Beautifulsoup\\Glamira\\project_glamira\\photo\\image_159474_GLAMIRA-Earring-Gaisma---B_alloy=yellow-585&stone1=emerald_4"
            ]
        }
    }
```