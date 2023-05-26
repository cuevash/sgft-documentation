# Webflow Projects
We as small design shop have  a goal of using **Webflow** as effective as possible for certain types of projects.
This document elaborate which projects will we focus on. 
Obviously **Webflow** has a huge range of possibilities and can be used to implement almost any project independently of its complexity.

Lets list the type of projects we do:

## Simple  Projects - Basic Static Websites
These are the simplest types of  projects and involve the creation of static web pages. They usually include a handful of pages (like Home, About, Contact, Services) and may contain basic elements like text, images, and simple contact forms. They lack complex interactions, animations, and dynamic content. An example might be a basic portfolio website or a small business website with basic information and no e-commerce functionality.

### Characteristics
* Static content
	* Updates by request
* Basic Animations
* Basic SEO
* Automatic responsive image generation
* Automatic and Manual Backups 
* reCAPTCHA (forms spam protection)
* GDPR Compliance
* Hosting:
	* Webflow (Basic - ~14$/month)
		* Forms support (500 per month)
	* Netlify (Maintenance cost)
		* Forms support (100/month + 19$ (1000/month) / 9$ (500 extra per month))
			* Extra cost for implementation
		* reCAPTCHA (forms spam protection)
			* Extra cost for implementation
* Cookies
	* CookieYes (Client Account)
		* Free for blogs and personal websites (25,000 pageviews/month)
		* ~10$/month For small business and startups (100,000 pageviews/month)
* Embedded Google Maps
* Basic Google Analytics (Client Account)

### Web Goal
* Landing Page
* Basic Portfolio (few updates)
* Small web with few static pages
* Few updates by request

## Intermediate Webflow Projects - Dynamic Websites and Blogs
These  projects leverage Webflow's CMS (Content Management System) capabilities. These websites not only contain static pages but also include dynamic content such as blog posts, news articles, or a gallery of projects. There may also be some usage of Webflow’s interactions and animations features to enhance the user experience. The complexity of these websites can vary significantly but they are more complex than basic static websites due to their dynamic content and potential for user interaction.
However, the interactivity level would remain fairly basic, utilizing Webflow's built-in interactions and animations for things like hover effects, basic show/hide interactions, and page transitions.
Some advanced features such as search , filtering actions will be considered as part of this level. But only at a low level of complexity.

### Characteristics
* All that is supported by Basic simple projects and:
* Hosting:
	* Webflow (CMS - ~23$/month)
		* 2.000 cms items
		* 1.000 forms
	* Webflow (Business - ~39$/month)
		* 2.000 cms items
		* 1.000 forms
* Google Maps
	* Embedded Maps
	* Advanced use such as (Client Account in Google Maps):
		*  showing pins for elements in collections
		*  Showing pop-up for elements in collections
		*  Others...
* Basic Google Analytics (Client Account)
* CMS Capabilities
	* Blog
	* Portfolio
	* News
	* etc...
	* Self Updating (Editor Mode Webflow)
* Basic Animation
* Limited Interactivity (Through the Finsweet Attributes library)
	* Basic buttons actions
	* Basic search widgets (Blogs, portfolio, news, etc...)
	* Basic filtering widgets (Blogs, portfolio, news, etc...)

### Web Goal
* Blogs
* Portfolio
* Limited self updating
	* Adding blog entries (Collection)
	* Adding Portfolio entries (Collection)
	* Adding News entries (Collection)

## Enhanced Dynamic Websites with High Interactivity
Websites in this category would take things a step further by implementing more complex interactions and animations. This could be achieved using advanced toolkits like Finsweet's libraries, which can greatly enhance the level of interactivity and the user experience. The use of Finsweet's libraries could allow for more complex features like sophisticated filtering systems, custom cursors, complex hover effects, and more advanced animations. Even though the use of such toolkits can significantly enhance the functionality and user experience, they don't quite reach the complexity of full e-commerce or API-integrated sites.
Using third-party libraries like Finsweet's can help designers unlock more of Webflow's potential and create more engaging and interactive websites, but they also require a higher level of understanding of how to implement and manage these added features.
### Characteristics
* All that is supported by Intermediate projects and:
* Complex Animations
* Complex Interactivity (Through the **Finsweet** Attributes library)
	* Buttons actions
	* Complex search widgets (Blogs, portfolio)
	* Complex filtering widgets (Blogs, portfolio)
	* Complex animations
	* Other Low code actions provided by the **Finsweet** Library
### Web Goal
* Blogs
* Portfolio
* Limited self updating
	* Adding blog entries (Collection)
	* Adding Portfolio entries (Collection)
* Web apps with advanced search/filter capabilities
* Data modelled and stored in collections

## ToDO:
### Anyway to use CMS for simple projects in a cheap and sot of easy way?

