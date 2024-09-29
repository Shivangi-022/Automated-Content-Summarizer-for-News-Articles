# Automated-Content-Summarizer-for-News-Articles
This project is a "Personalized News Summarizer" built with Streamlit. Users input preferences (country, category, source, role), and the app uses Googlesearch-Python to retrieve relevant news articles. It scrapes and summarizes articles with BeautifulSoup, and converts summaries into audio using gTTS for easy listening.

This project is a **Personalized News Summarizer Web Application** built using **Streamlit**, designed to provide users with customized news content and summaries. The application allows users to input their preferences, such as country, news category, specific sources, and their role (e.g., student, lawyer), and then uses **Google search** to find relevant news articles based on these inputs.

### Key Features:
1. **User Input for Preferences**: Users can specify the country, news category (e.g., technology, business), a specific news source (e.g., BBC News), and their professional role to generate a personalized news query.
   
2. **Google Search Integration**: The application uses **Googlesearch-Python** to search for relevant news articles based on the user's query. It then retrieves the top articles matching the user's preferences.

3. **Article Summarization**: Users can select any of the returned articles, and the app scrapes the article using **BeautifulSoup** to extract and summarize the main content (first three paragraphs).

4. **Text-to-Speech Functionality**: Once an article is summarized, the app converts the summary into an audio file using **gTTS (Google Text-to-Speech)**, allowing users to listen to the summary directly within the app.

5. **API Integration**: The app is set up with **Groq API**, though it appears to be a placeholder for potential integration with an AI summarization tool.

### Technical Stack:
- **Streamlit**: For building the web interface.
- **Googlesearch-Python**: To perform Google searches and retrieve news article URLs.
- **BeautifulSoup**: For web scraping the content of the articles.
- **gTTS**: To convert the article summary into audio format.
- **Groq API**: Placeholder for AI functionality, possibly to enhance the summarization capabilities in the future.

### Workflow:
1. **User Preferences**: The user inputs preferences through the Streamlit form (country, category, source, role).
2. **News Search**: Based on the input, the app generates a search query and retrieves a list of relevant news articles using Google Search.
3. **Article Selection**: The user selects an article from the list, and the app scrapes and summarizes the article content.
4. **Audio Summary**: The app uses gTTS to generate an audio version of the summary for the user to listen to.

This project is ideal for users seeking a personalized, summarized, and accessible news-reading experience.
