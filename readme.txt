News App  

Overview  
The News App is a web-based application that fetches and displays news articles based on various categories and search queries. It utilizes the [News API](https://newsapi.org/) to fetch real-time news articles.  

Features  
- Fetches latest news based on predefined categories (Education, IPL, Entertainment, Finance, Technology, Politics).  
- Search functionality to find news on a specific topic.  
- Responsive and interactive UI.  
- Dynamic news cards displaying images, headlines, descriptions, and sources.  

Technologies Used  
- HTML - Structure of the application.  
- CSS - Styling using Google Fonts and responsive design.  
- JavaScript - Fetching and displaying news dynamically.  
- News API - External API to get real-time news data.  

File Structure  

/NewsApp
│── index.html    Main HTML structure
│── style.css     Styling and layout
│── script.js     JavaScript for fetching news and handling UI interactions
│── assets/       Contains images and logos


 Setup Instructions  
1. Clone the repository or download the source files.  
2. Open `index.html` in a browser.  
3. The app will load the latest news from India by default.  
4. Click on category links or search for custom news.  

 API Key Configuration  
- This project requires an API key from [News API](https://newsapi.org/).  
- The API key is stored in `script.js`. Replace the existing key with your own if needed:  
  javascript
  const API_KEY = "your_api_key_here";
  

 Usage  
- Click on any category in the navigation bar to fetch news from that topic.  
- Use the search bar to enter a query and find news related to that keyword.  
- Clicking on a news card will open the full article in a new tab.  



