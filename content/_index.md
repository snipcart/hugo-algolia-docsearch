---
title: Hugo
type: docs
---

# Products we use

## Hugo

**Hugo** is a [static site generator](/wiki/Web_template_system#Static_site_generators "Web template system") written in [Go](/wiki/Go_(programming_language) "Go (programming language)"). Originally created by Steve Francia in 2013, Hugo has seen a great increase in both features and performance thanks to current lead developer Bjørn Erik Pedersen (since v0.14 in 2015) and other contributors. Hugo is an open source project licensed under the [Apache License](/wiki/Apache_License "Apache License") 2.0.

Being able to generate most websites within seconds (at < 1 ms per page), Hugo is renowned as "The world’s fastest framework for building websites" thanks to not only it being built with Go but also conscientious efforts by its developers to benchmark and increase performance. Its lightning speed and evolving feature set led to a huge increase its popularity. For example, in July 2015, [Netlify](/wiki/Netlify "Netlify") began providing Hugo hosting, and in 2017, [Smashing Magazine](/wiki/Smashing_Magazine "Smashing Magazine") completed its redesign of their website, migrating from [WordPress](/wiki/WordPress "WordPress") to a [JAMstack](/wiki/Netlify#JAMstack "Netlify") solution with Hugo.

### Features

Hugo takes data files, i18n bundles, configuration, templates for layouts, static files, and content written in [Markdown](/wiki/Markdown "Markdown") and renders a static website. Some notable features are multilingual support, image processing, custom output formats, and shortcodes. Nested sections allow for different types of content to be separated. E.g. for a website containing a blog and a podcast.

## Algolia

**Algolia** is a U.S. [startup company](/wiki/Startup_company "Startup company") offering a [web search](/wiki/Web_search "Web search") product through a SaaS ([software as a service](/wiki/Software_as_a_service "Software as a service")) model.

## Company

Algolia was founded in 2012 by Nicolas Dessaigne and Julien Lemoine, who are originally from Paris, France. It was originally a company focused on offline search on mobile phones. Later it was selected to be part of [Y Combinator](/wiki/Y_Combinator_(company) "Y Combinator (company)")'s Winter 2014 class.

Starting with two [data centres](/wiki/Data_centre "Data centre") in Europe and the US, Algolia opened a third centre in Singapore in March 2014, and as of 2016, claimed to be present in 47 locations across 15 worldwide regions. It serves roughly 7,000+ customers, handling 60 billion user queries per month. Those customers span [e-commerce](/wiki/E-commerce "E-commerce"), media and other industries, including [DC Shoes](/wiki/DC_Shoes "DC Shoes"), [Medium](/wiki/Medium_(website) "Medium (website)") and [vevo](/wiki/Vevo "Vevo"). In May 2015, Algolia received $18.3M in a [series A investment](/wiki/Series_A_round "Series A round") from a financial group led by [Accel Partners](/wiki/Accel_Partners "Accel Partners"), and in 2017 a $53M series B investment, also led by Accel Partners From June 2016 to June 2017, the usage of Algolia by small websites has increased from 632 to 1,591 in the "top 1mio websites" evaluated by [BuiltWith](/wiki/BuiltWith "BuiltWith"). In the same timeframe, BuiltWith recorded no significant usage increase among their "top 10k homepages".

## Products and Technology

The Algolia model provides [search as a service](/wiki/Search_as_a_service "Search as a service"), offering web search across a client's website using an externally hosted [search engine](/wiki/Search_engine "Search engine"). Although in-site search has long been available from general web search providers such as Google, this is typically done as a subset of general web searching. The search engine [crawls](/wiki/Web_crawler "Web crawler") or [spiders](/wiki/Web_crawler "Web crawler") the web at large, including the client site, and then offers search features restricted to only that target site. This is a large and complex task, available only to large organisations at the scale of Google or Microsoft.

Algolia's product only indexes their clients' sites and so the search task is far simpler. Data for the client site is [pushed](/wiki/Push_model "Push model") from the client to Algolia via a [RESTful](/wiki/RESTful "RESTful") [JSON](/wiki/JSON "JSON") API, then the search box is added simply to the client's web pages. This search model is intended to give the performance and sophistication advantages of a full in-house search engine operating on the native web site back-end database, but with the simplicity of setup of using a site-restricted Google search.

### Products

Algolia claims a number of advantages for their approach, including speed of response from searching a single site rather than the entire web. Moreover, as Algolia's search can be tailored to the client site, its known structure and its [metadata facets](/wiki/Faceted_metadata "Faceted metadata"), the search offered can be smarter and more site-specific than a generalised web text search. This improves the relevance of search results as searching may take the [semantics](/wiki/Semantic_web "Semantic web") of site content into account. A web site selling both [puppies](/wiki/Puppy "Puppy") and [dog clutches](/wiki/Dog_clutch "Dog clutch") could avoid the search confusions and [homonymy](/wiki/Homonym "Homonym") that bedevil the simple text-based search approaches.

Algolia emphasize their ability to provide instantaneous, multi-platform and typo-tolerant features. Algolia's software is closed source. They do however contribute to the open source community to an extent. Two examples are Algolia Place and Algolia Document.

### API

Algolia provides their search service via various APIs. The Rest API provides basic features of search, analysis and monitoring. There are 10 supported languages and platforms for client usage. Supported languages include [Python](/wiki/Python_(programming_language) "Python (programming language)"), [Ruby](/wiki/Ruby_(programming_language) "Ruby (programming language)"), [PHP](/wiki/PHP "PHP"), [JavaScript](/wiki/JavaScript "JavaScript"), [Java](/wiki/Java_(programming_language) "Java (programming language)"), [Go](/wiki/Go_(programming_language) "Go (programming language)"), [C#](/wiki/C_Sharp_(programming_language) "C Sharp (programming language)"), [Scala](/wiki/Scala_(programming_language) "Scala (programming language)"). Two mobile platforms, [iOS](/wiki/IOS "IOS"), [Android](/wiki/Android_(operating_system) "Android (operating system)"), are supported. Algolia can be also integrated with four web frameworks: [Ruby on Rails](/wiki/Ruby_on_Rails "Ruby on Rails"), [Symfony](/wiki/Symfony "Symfony"), [Django](/wiki/Django_(web_framework) "Django (web framework)") and [Laravel](/wiki/Laravel "Laravel"). For user interface, Algolia has a few UI libraries options to choose from.

Besides these products, Algolia also has integration with other open source and third-party software, including [Drupal](/wiki/Drupal "Drupal"), [WordPress](/wiki/WordPress "WordPress") and [Magento](/wiki/Magento "Magento").

### Infrastructure

Algolia documented one attempt to remove all single points of failure in their architecture and proposed a worldwide infrastructure called _Distributed Search Network_ to efficiently reply to a search query from any location.

The DSN feature allows to set the locations in Algolia's network where the data should be duplicated. The API and queries are routed from the end-user's browser or mobile application to the closest location in the network. That setup helped reduce processing latency for the end users, and improves availability for their searches.
