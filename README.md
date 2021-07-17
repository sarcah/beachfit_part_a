# Sarah Cahill and Punit Dharmadhikari
## T3A2 Full Stack Application - Part A

<br>

#### R1. Description and Purpose
Beachfit and Wellbeing is a fitness company, offering group bootcamps on Coogee Beach. This business was sold to a new owner two years ago, but the website has not been changed since she took ownership of the business. All the content is from the previous owner. The website also has some design issues (as shown with the search bar in the homepage screenshot below), and is not completely responsive. 

!["Original Homepage screenshot"](/img/Original_home.png)
<sub><sup>Source: http://www.beachfitandwellbeing.com/</sup></sub>

Oversized footer on the laptop size:
!["Original Homepage footer screenshot"](/img/Original_footer.png)
<sub><sup>Source: http://www.beachfitandwellbeing.com/</sup></sub>

The website offers no administrator access, and any changes have to be made in the code. The current owner has no technical skills, and would like an easy way to change things like prices and timetable on the website.

The purpose of this website is to appeal to new customers for the bootcamps. The company has an Instagram page, and having a website allows the company to provide additional information (like pricing), and to provide added legitimacy to the business.


#### Functionality / features
The MVP site will have the following pages, accessible for all to view:
- **Home**
- **About**
- **Pricing**
- **Timetable**
- **FAQs**
- **Contact**

Users will be able to view all pages of the site, to get information about what the classes involve, when they are held and how much they cost. They are also invited to get in contact for a free trial.

Additionally, there is also a client/administrator site. Below pages will be designed only for client to view
- **Login page**
- **Administrator Dashboard**

The client will be able to visit a login page, where they are then granted access to the dashboard. This will allow them to edit the FAQs and prices, so they can update them as needed. 

The below features are stretch goals, and will be included if time permits.
- Blog page - stored in databases, and ability for administrator to post.
- Search bar
- Link to instagram feed
- Add booking link to external Mindbody app for classes
- Implement live chat
- Would initially deploy on Netlify and Heroku, but then would look to use the current domain name.


#### Target audience
The target audience for this website is very much new customers, rather than existing members. Once they become regular members and attendees, the main method of communication is a whatsapp group and bookings are also conducted through the Mindbody app. This website is for the acquisition of customers, rather than retention. 

New customers to a bootcamp are often apprehensive about what will be involved, and would like as much information as possible. The purpose of this site is to provide them with this information, show them what a great experience the bootcamps are, and encourage them to start a free trial. The way to get in contact with the owner should also be very clear, and provide as little barrier to purchase/trial as possible.  

The client/owner is also a target audience in a sense. She would like to be able to update her own website without asking a developer. To meet this requirement, an administrator log in will be added, which leads to an easy to use dashboard, allowing the administrator to update FAQs and pricing, without touching the code. 


#### Tech Stack

- Ruby on Rails – backend framework
- React – frontend framework
- HTML, CSS and JS - frontend
- PostgreSQL – database
- Devise gem – for user authentication and authorisation
- Devise-jwt gem – to ensure that cookies are ‘blacklisted’ and can never be used again once destroyed
- Figaro gem – to store environment variables in backend (Rails)
- DotEnv – to store environment variables in frontend (React)
- Craco – a script manager for running Tailwind applications
- Material-UI – a CSS framework built by Google that contains pre-render components – very handy for quick user interface
- Tailwind CSS – another CSS framework for quick adding styling and easy-to-install templates
- Axios – to send HTTP requests (GET, POST, PUT, DELETE) from React frontend to the Rails backend – makes it easier than using fetch requests

**Tools**
- Git and Github – source control
- Heroku/Netifly - deployment
- Trello – project management 
- Balsamiq - wireframes


#### Sitemap

!["Beachfit Sitemap"](/img/sitemap.png)


#### Entity Relationship Diagram

!["Beachfit ERD"](/img/ERD.png)

<details>
<summary> R2. Dataflow Diagram </summary>

!["Beachfit Dataflow Diagram"](/img/DFD.png)
</details>


<details>
<summary> R3. Application Architecture Diagram </summary>

!["Beachfit Application Architecture Diagram"](/img/AAD.png)
</details>

<details>
<summary> R4. User Stories </summary>

**Client**
*MVP*

As a client, I want to be able to log in to the site and see a dashboard, that is secure and easy to use. 
As a client, I want to be able to add/edit/delete FAQs from the site through the administrator dashboard.
As a client, I want to be able to add/edit/delete the pricing and membership options from the site through the administrator dashboard.

*Stretch Targets*
As a client, I want to be able to add/edit/delete Blog posts from the site.
As a client, I want to be able to add/edit/delete photos from the site.
As a client, I want potential customers to find it easy to get in contact to set up a free trial, and encourage them to do so.
As a client, I want potential customers to have a seamless user experience. 
As a client, I want to utilise the existing web page (http://www.beachfitandwellbeing.com/)

**Potential Customer**
*MVP*
As a user, I want to easily interact with the website, and find the information I need.
As a user, I want to get an accurate idea of what the bootcamp sessions are like before attending. 
As a user, I want the frequently asked questions to be easily accessible and to cover topics I am interested in.
As a user, I want to have clear information regarding pricing that I can access upfront.
As a user, I want multiple options to contact (phone, email, Instagram account). 

*Stretch Targets*
As a user, I want to be able to link directly through to the booking platform from the website. 
As a user, I want to have a keyword search capability, to search all the content on the site. 
As a user, I want the ability to live chat with the business owner.
As a user, I want the first search result to appear on google when I search ‘beachfit’ (this happens when the existing website address is used without additional investment in SEO).
</details> 

<details>
<summary> R5. Wireframes </summary>

Initial round of wireframes done (version one) completed, then reviewed by team and presentated to Client. After discussion with Client and research into tailwind templates, some pages revised and version two created.

!["Wireframes"](/img/wireframes.png)
</details>

<details>
<summary> R6. Trello Screenshots </summary>

Trello was used as a management tool for the project. Different cards were created for each rubric to ensure requirements were met, and assigned to each team member (or both). Comments used to add to each card to ensure all team members were across what had been done and what still needed to be done.
Some coding components for Part B entered to start planning and researching for next part of the website development, including stretch components.

https://trello.com/b/QOcKR4Y2/rails-react-app 

Day 1:
!["Trello 10 July"](/img/Trello_Screenshots/Trello_100721.png)

Day 2:
!["Trello 11 July"](/img/Trello_Screenshots/Trello_110721.png)

Day 3:
!["Trello 12 July"](/img/Trello_Screenshots/Trello_120721.png)

Day 4:
!["Trello 13 July"](/img/Trello_Screenshots/Trello_130721.png)

Day 5:
!["Trello 14 July"](/img/Trello_Screenshots/Trello_140721.png)

Day 6:
!["Trello 15 July"](/img/Trello_Screenshots/Trello_150721.png)

Day 7:
!["Trello 16 July"](/img/Trello_Screenshots/Trello_160721.png)
</details>

