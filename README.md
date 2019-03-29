# max-advisor


### Problem Statement

<p>As a hotel manager or owner, I’d like to make the most informed decision when setting daily rates. Currently, our rates are adjusted based on our own supply and demand (i.e. hotel occupancy) and major holidays and known events in the area. Ideally, I’d like to understand the market trends in my area to see how occupation and daily rates are adjusted throughout the year so I’m confident and in alignment with the market when setting my own rates on any given day.</p>


### Technologies I want to use.
1. [Vue](https://vuejs.org/)
2. [Materialize](https://materializecss.com/)
3. [Express](https://expressjs.com/)
4. [Postgres](https://www.postgresql.org/)
5. API's
    * [Google places API](https://developers.google.com/places/web-service/intro)
    * [Expedia API](https://developer.expediapartnersolutions.com/documentation/rapid-content-docs-2-2/)
6. O-Auth
7. [Chart.js](https://www.chartjs.org/)
8. [d3](https://d3js.org/)
9. [Knex](https://knexjs.org/)

### Wire Frame
[Wire frame link](https://trello.com/c/lQMXS1IH/13-https-wireframecc-pro-edit-236267)

<img alt = 'homepage' src = '/Users/logantrujillo/galvanize/q4/capstone/max-advisor/src/assets/home-page.png' width=400 height=400/>
<img alt = 'analytics-page' src='/Users/logantrujillo/galvanize/q4/capstone/max-advisor/src/assets/analytics-page.png' width=400 height=400/>

### Color Pallete

<img alt = 'color pallete' src = '/Users/logantrujillo/galvanize/q4/capstone/max-advisor/src/assets/color-pallete.png'>

### Server Route Plan
```
GET
  ('/')
    - Return array of 10 nearest hotels prices based on user object/token sent to server.
Post
  ('/')
    - Create a new user
    - Send user's daily and monthly occupation rates 
Delete        
  ('/')
    -Delete a user and their connected occupation rates
Puts 
  ('/')
    -Update a user's info and occupation info    
```
### User Stories
[User Stories Link](https://trello.com/b/7VoaR6Jo/maxadvisor)



