# Project Plan and Design
## 1. Project Goals:
**Main Objective**: Develop a comprehensive web application that displays detailed cricket player information and performance analytics.<br>
**Sub-Objectives:**
- Scrape player data from leading cricket websites.
- Store the scraped data in a well-designed database.
- Create a user-friendly interface to display player information.
- Implement advanced filtering and searching functionalities.
- Integrate data analytics and prediction features.
  
## 2. Technology Stack:
**Web Scraping:** Python (BeautifulSoup, Scrapy, Selenium) <br>
**Backend:** Node.js / Django / Flask <br>
**Frontend:** React.js / Vue.js <br>
**Database:** PostgreSQL / MySQL / MongoDB <br>
**Caching:** Redis <br>
**Search:** Elasticsearch <br>
**Data Visualization:** D3.js / Chart.js <br>
**Hosting:** AWS / Heroku / DigitalOcean <br>

## 3. Detailed Steps:
1. **Data Collection and Storage:**

   - **Web Scraping Plan:**
     - Scrape player data from ESPN CrickInfo.
     - Use BeautifulSoup and Selenium to gather comprehensive player data.
     - Clean and preprocess the data to ensure accuracy.
   - **Database Design:**
      - Create an Entity-Relationship (ER) diagram to model the data structure.
      - Define entities: Players, Matches, Records, Teams.
      - Establish relationships and create tables: Players, Matches, BattingStats, BowlingStats.
      -  Implement the database schema and populate it with the scraped data.
2. **Backend Development:**

   - **API Development:**
       - Design RESTful APIs for CRUD operations on Player, Team, and Match data.
       - Integrate Redis for efficient data caching.
       - Set up Elasticsearch for advanced search functionalities and index the data.
   - **Server Deployment:**
       - Host the backend server on AWS/Heroku/DigitalOcean.
       - Ensure the server is secure, scalable, and reliable.
3. **Frontend Development:**

    - **UI/UX Design:**
        - Create wireframes and design a user-friendly interface for displaying player profiles, search, and team selection features.
        - Use React.js/Vue.js to build a dynamic and responsive frontend.
    - **API Integration:**
            - Connect the frontend with backend APIs to fetch and display data.
            - Implement interactive charts and graphs using D3.js/Chart.js for data visualization.
4. **Advanced Filtering and Search:**

    - **Elasticsearch Configuration:**
        - Set up and configure Elasticsearch for powerful and flexible search capabilities.
        - Design complex search queries to enable advanced filtering options on the frontend.
    - **Frontend Integration:**
        - Implement the search and filter functionalities on the user interface.
5. **Ranking Algorithm:**

   - **Algorithm Design:**
        - Develop a ranking algorithm to select the best 11 players from a pool of 22.
        - Consider constraints such as player roles (top-order, middle-order, lower-order batsmen, spinners, all-rounders, and pacers).
   - **Implementation:**
        - Implement the algorithm on the backend.
        - Create a frontend feature for users to select and rank players based on the algorithm.
6. **Data Analytics and Prediction:**

    - **Data Analysis:**
        - Perform data analysis to generate meaningful insights and reports.
        - Use statistical methods and machine learning models for predictions.
    - **Visualization and Reporting:**
        - Develop dashboards to visualize data analytics and predictions.
        - Allow users to view detailed reports and trends.

## 4. ER Diagram:
<img src = ./static/CricketInsight.png>

## 5. Phased Work:
- **Phase 1**: Web Scraping and Database Design (3 weeks)
- **Phase 2:** Backend Development and API Creation (4 weeks)
- **Phase 3:** Frontend Development and User Interface (5 weeks)
- **Phase 4:** Advanced Filtering and Search Feature (3 weeks)
- **Phase 5:** Ranking Algorithm and Team Selection (2 weeks)
- **Phase 6:** Data Analytics and Prediction (4 weeks)
  
## 6. Timeline and Deliverables:
- **Phase 1:** Complete web scraping scripts and database schema.
- **Phase 2:** Develop and deploy backend with API endpoints.
- **Phase 3:** Build and integrate frontend with a focus on usability.
- **Phase 4:** Implement and optimize search and filter functionalities.
- **Phase 5:** Design and deploy the ranking algorithm and team selection interface.
- **Phase 6:** Generate analytics dashboards and prediction models.
