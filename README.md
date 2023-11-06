# MediSimplify
IOS Capstone Project

# **Assignment 1: Initial GitHub Repository Setup**

---

## **Assignment 1: Initial GitHub Repository Setup**

### **GitHub Repository: `MediSimplify`**

**Tasks:**

1. **Repository Creation:**
    - Name: `MediSimplify`
    - Description: "Simplifying medical research for everyone."
2. **[Brainstorm.md](http://brainstorm.md/)**:
    - **Idea Genesis:** Recognizing the challenge faced by many in comprehending dense research articles.
    - **User Base:** Medical students, professionals, educators, journalists, and health enthusiasts.
    - **Challenges:** Handling diverse article structures, achieving precise AI summaries, and creating an intuitive UI/UX.
3. **[Readme.md](http://readme.md/)**:
    - **Project Title:** MediSimplify
    - **Brief Description:** A mobile app designed to fetch medical research articles and employ AI for generating concise summaries and pivotal metrics.
    - **Core Functionalities:**
        1. Interactive search mechanism.
        2. Search result display.
        3. Comprehensive article view.
        4. AI-enhanced insights.
        5. Local storage for favorites and recent searches.
    - **APIs Used:** NLM for research articles, OpenAI's ChatGPT for data analysis.
4. **Wireframes** (using tools like Figma or Sketch):
    - Search interface.
    - Article listing page.
    - Detailed article view, including AI analysis.

---

## **Assignment 2: Sprint Planning and Development**

### **Step 1: Identify Main Features**

1. **Search Bar**: An intuitive interface for users to input their queries.
2. **Article ListView**: Displays the fetched articles in a list/table format.
3. **ArticleDetailView**: Showcases the selected article and contains an option for AI-enhanced summary.
4. **AI Analysis Integration**: User-initiated AI insight generation.
5. **Favorites & Recent Searches**: Allows users to bookmark articles and also see their search history.

### **Step 2: Breakdown into Sprints**

**Sprint 1: Foundations and Basics**

- Setup the Swift project.
- Configure basic networking to connect with the NLM API.
- Display a rudimentary list of articles.

**Sprint 2: UI/UX Enhancements**

- Refine the search mechanism.
- Design and develop an attractive table view for article listings.
- Incorporate pagination or infinite scroll for extensive search results.

**Sprint 3: Dive into Details and AI**

- Construct the ArticleDetailView to present articles in-depth.
- Seamless integration of ChatGPT for AI summaries and metrics.
- Introduce interactive UI elements for displaying AI insights in a user-friendly manner.

**Sprint 4: Final Touches and Persistence**

- Fine-tune AI summary outputs.
- Integrate local data persistence using Swift's CoreData or Realm.
- Design and implement a favorites section and recent search list.

### **Step 3: Define Weekly Goals for Each Sprint**

**Sprint 1 Goals:**

- **Specific:** Set up the project infrastructure and get preliminary networking in place.
- **Measurable:** By the end of the week, successfully fetch and show a list of articles.
- **Achievable:** Use Swift's built-in networking or Alamofire.
- **Relevant:** Establishing the base for further development.
- **Time-bound:** Conclude in one week.

**Sprint 2 Goals:**

- **Specific:** Enhance the overall UI/UX for users.
- **Measurable:** By the week's end, achieve a visually appealing and functional search and result display.
- **Achievable:** Leverage SwiftUI or UIKit's capabilities.
- **Relevant:** Ensures user engagement and satisfaction.
- **Time-bound:** Complete within a week.

**Sprint 3 Goals:**

- **Specific:** Offer users an extensive view of articles and introduce AI capabilities.
- **Measurable:** Post-sprint, articles should be viewable in-depth with an AI summary option.
- **Achievable:** Integration of OpenAI's API for data interpretation.
- **Relevant:** Crucial for the core function of the app.
- **Time-bound:** One week's duration.

**Sprint 4 Goals:**

- **Specific:** Refinement and incorporation of data persistence.
- **Measurable:** By the end of the sprint, users should be able to save favorite articles and revisit recent searches.
- **Achievable:** Utilize CoreData or Realm for data storage.
- **Relevant:** Enhances user experience by preventing repetitive searches.
- **Time-bound:** Conclude in one week.

---

---

1. **Sprint 1: Set up the project and integrate basic Read-only Networking.**
    - Initialize the project repository and set up the basic Swift project.
    - Implement basic networking tools, possibly using Alamofire or URLSession.
    - Connect to the NLM API and ensure you can retrieve raw article data.
2. **Sprint 2: Design and implement the Home Screen.**
    - Sketch or wireframe the UI/UX for the home screen.
    - Build the Home Screen UI in SwiftUI or UIKit.
    - Implement the search bar functionality and display search results in a list or table view.
3. **Sprint 3: Build the Article Detail screen.**
    - Design the Article Detail view.
    - Implement the navigation from the list item to the detail view.
    - Display raw article data in the detail view.
4. **Sprint 4: Implement Summarization Functionality and Local Data Persistence.**
    - Integrate with the OpenAI GPT API and create prompts for data summarization.
    - Display summarized data in a dedicated section of the Article Detail screen or in a separate view.
    - Implement local data persistence to save user searches, favorite articles, or any other relevant data using tools like CoreData or Realm.


