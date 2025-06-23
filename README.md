<div align="center">
  <img src="https://i.imgur.com/cDW81Uz.png" />
</div>
<h2 align="center" id="juandergo-multi-agentic-ai-powered-travel-planner">JuanderGo: Multi Agentic AI Powered Travel Planner</h2>

<p align="center">
  <a href="https://juandergo.aratilismk.com/">
    <img src="https://img.shields.io/badge/-🌏%20JuanderGo Deployed App-orange?style=for-the-badge" alt="JuanderGo" />
  </a>
  <a href="https://www.canva.com/design/DAGrKXZZjW8/zDj54wt_vRTjQIb-dyHWag/edit?utm_content=DAGrKXZZjW8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">
    <img src="https://img.shields.io/badge/-📊%20Final%20Pitch%20Deck-blueviolet?style=for-the-badge" alt="Final Pitch Deck" />
  </a>
</p>

---

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Data Acquisition and Storage](#data-acquisition-and-storage)
- [Feature Highlights](#feature-highlights)
- [Intelligent Search](#intelligent-search)
- [Agentic AI Agents](#agentic-ai-agents)
- [Chatbot](#chatbot)
- [Automated Email Inquire](#automated-email-inquire)
- [How to Access JuanderGO Online](#how-to-access-juandergo-online)
- [How to Run JuanderGO Locally](#how-to-run-juandergo-locally)
- [Repository Structure](#repository-structure)
- [Team Details](#team-details)

---

<h2 id="project-overview">🧠 Project Overview</h2>

<!-- JuanderGo Overview Image -->
<p align="center">
  <img src="https://i.imgur.com/wjXY3gQ.png" alt="JuanderGO Overview" width="80%" style="border-radius: 12px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);"/>
</p>

<!-- Project Description -->
<p align="justify" style="font-size: 16px; line-height: 1.6;">
  <strong>JuanderGO</strong> is an AI-powered travel itinerary generator designed to simplify and personalize trip planning across the Philippines. It addresses the challenge many travelers face: spending hours researching destinations, activities, and logistics.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  By integrating intelligent search, agentic AI agents, and tourism data sourced from the Department of Tourism’s (DoT) accredited establishments and official tourism website, JuanderGO creates tailored itineraries in minutes. It's built for tourists, both local and foreign, who want meaningful and efficient travel experiences without the hassle.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  By encouraging domestic exploration and supporting DOT-accredited businesses, JuanderGO contributes to the growth of local tourism, uplifts regional communities, and harnesses the power of AI to make travel across the Philippines more accessible and enriching.
</p>

---

<h2 id="tech-stack">🛠️ Tech Stack</h2>

<!-- JuanderGo Techstack Overview Image -->
<p align="center">
  <img src="https://i.imgur.com/l4bQLU5.png" alt="JuanderGO Techstack Overview" width="80%" style="border-radius: 12px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);"/>
</p>

<!-- Techstack Summary -->
<p align="justify" style="font-size: 16px; line-height: 1.6;">
  This section highlights the core technologies and tools used to build <strong>JuanderGO</strong>. It covers everything from the agentic AI framework that powers intelligent itinerary generation, to the frontend interface, data processing workflows, vectorization methods, external API integrations, and deployment infrastructure. Each layer of the stack plays a vital role in ensuring a seamless, responsive, and personalized travel planning experience for users.
</p>

<div align="center" style="width: 100%;">
  <table style="width: 100%;">
    <thead>
      <tr>
        <th>#</th>
        <th>Tool / Technology</th>
        <th>Category</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <!-- Frontend -->
      <tr><td>1</td><td>Streamlit</td><td>Frontend</td><td>Framework for building interactive Python-based web apps.</td></tr>
      <tr><td>2</td><td>Figma</td><td>Frontend</td><td>Used for designing UI/UX wireframes and visual layouts.</td></tr>
      <tr><td>3</td><td>Bootstrap Icons</td><td>Frontend</td><td>Adds consistent visual icons to improve the app's visual clarity.</td></tr>
    <!-- Agentic AI Framework -->
      <tr><td>4</td><td>CrewAI</td><td>Agentic AI Framework</td><td>Orchestrates multiple autonomous agents that collaborate to generate travel recommendations.</td></tr>
      <tr><td>5</td><td>Langchain</td><td>Agentic AI Framework</td><td>Connects AI models with tools and data sources to enable contextual understanding and task execution.</td></tr>
      <!-- Web Scraping -->
      <tr><td>6</td><td>Undetected ChromeDriver</td><td>Web Scraping</td><td>Allows headless and stealth browsing to access dynamic content undetected.</td></tr>
      <tr><td>7</td><td>BeautifulSoup</td><td>Web Scraping</td><td>Parses HTML pages to extract structured information from static websites.</td></tr>
      <tr><td>8</td><td>Selenium</td><td>Web Scraping</td><td>Automates browser interaction for dynamic or JavaScript-heavy pages.</td></tr>
      <!-- Data Preprocessing -->
      <tr><td>9</td><td>Regex</td><td>Data Preprocessing</td><td>Extracts structured patterns like location names and dates from raw text.</td></tr>
      <tr><td>10</td><td>Pandas</td><td>Data Preprocessing</td><td>Handles data manipulation, cleaning, and transformation tasks.</td></tr>
      <tr><td>11</td><td>NLTK</td><td>Data Preprocessing</td><td>Performs natural language preprocessing such as tokenization and filtering.</td></tr>
      <!-- Vectorization -->
      <tr><td>12</td><td>Sklearn (TFIDF)</td><td>Vectorization</td><td>Converts textual data into weighted keyword vectors for keyword relevance.</td></tr>
      <tr><td>13</td><td>OpenAI Embedding Model</td><td>Vectorization</td><td>Generates semantic vectors to enable meaning-based (not just keyword-based) search.</td></tr>
      <tr><td>14</td><td>QDrant Cloud</td><td>Vectorization</td><td>A vector database that stores embeddings and supports fast similarity search.</td></tr>
      <!-- APIs -->
      <tr><td>15</td><td>Google Maps API</td><td>API</td><td>Enables location search and mapping services within the itinerary planner.</td></tr>
      <tr><td>16</td><td>Google Flights (SerpAPI)</td><td>API</td><td>Fetches flight pricing and route suggestions based on destination and dates.</td></tr>
      <tr><td>17</td><td>Google Search API</td><td>API</td><td>Supports retrieval of up-to-date location-specific details and links.</td></tr>
      <tr><td>18</td><td>Google Weather API</td><td>API</td><td>Provides real-time and historical weather forecasts for informed planning.</td></tr>
      <!-- Programming Language -->
      <tr><td>19</td><td>Python</td><td>Programming Language</td><td>Primary language for backend logic, AI orchestration, scraping, and APIs.</td></tr>
      <!-- Deployment -->
      <tr><td>20</td><td>AWS EC2 Windows Server</td><td>Deployment</td><td>Used to deploy and host JuanderGO online. The Windows-based EC2 instance runs the Streamlit web app and all supporting backend services.</td></tr>
      <!-- Tools -->
      <tr><td>21</td><td>VSCode</td><td>Tools</td><td>Code editor for development.</td></tr>
      <tr><td>22</td><td>GitHub</td><td>Tools</td><td>Version control and project hosting platform.</td></tr>
      <tr><td>23</td><td>Jupyter Notebook</td><td>Tools</td><td>Used for experimenting with data and prototyping AI logic.</td></tr>
      <tr><td>24</td><td>Canva</td><td>Tools</td><td>Visual asset creation for presentations and UI mockups.</td></tr>
      <tr><td>25</td><td>OBS Studio</td><td>Tools</td><td>Recording tool used for screen captures and demo videos.</td></tr>
    </tbody>
  </table>
</div>


---

<h2 id="data-acquisition-and-storage">📦 Data Acquisition and Storage </h2>

<h3> 📊 Data in Numbers </h3>
<img src = "https://i.imgur.com/Rw2q07U.png">

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  This section showcases the extensive scope of our tourism database, covering all 17 regions and 127 provinces across the Philippines. It includes key figures such as the number of tourist attractions, accredited enterprises, tour guides, events, and more. Powered by advanced search capabilities including keyword, semantic, and hybrid search, users can explore data intelligently and intuitively to discover travel insights and plan their journeys more effectively.
</p>

<h3> 🗺️ Data Sources </h3>
<!-- JuanderGo Data Sources Overview Image -->
<p align="center">
  <img src="https://i.imgur.com/eEBjts7.png" alt="JuanderGO Data Sources" width="80%" style="border-radius: 12px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);"/>
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  This section includes all sources and methods used to gather and organize the tourism data that powers <strong>JuanderGO</strong>. The platform draws from government-accredited and official datasets to ensure the accuracy and reliability of its recommendations. These sources include the Tourism Promotions Board’s official website, the Department of Tourism’s accredited enterprise listings, and additional regional datasets acquired through formal requests. The data collected serves as the foundation for the intelligent search engine and agent-based itinerary generation system.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  <strong><a href ="https://thephilippines.online/" target="_blank">1. Tourism Promotions Board – The Philippines Online</strong><br>
  This is the official tourism website of the Philippines managed by the Tourism Promotions Board (TPB), an attached agency of the Department of Tourism. It provides curated destination content, travel guides, featured spots, and promotional campaigns aimed at both local and international travelers. JuanderGO extracts descriptive content, featured locations, and travel ideas from this source to enrich its itinerary suggestions with verified and inspiring information.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  <strong><a href ="https://beta.tourism.gov.ph/accreditations/#dot-accredited" target="_blank">2. Department of Tourism Accredited Tourism Enterprises</strong><br>
  The Department of Tourism (DoT) provides a regularly updated list of officially accredited tourism-related businesses in the Philippines. This includes hotels, restaurants, tour operators, and other establishments that meet government standards. JuanderGO uses this dataset to ensure all suggested accommodations and services are trustworthy, safe, and DoT-accredited — boosting traveler confidence and supporting compliant local businesses.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  <strong><a href ="https://drive.google.com/drive/folders/1DRI7HWoVZNM8zPV0td56pdDfq2NMdT4-" target="_blank">3. Requested Regional Data from DoT Offices</strong><br>
  To complement publicly available data, additional datasets were formally requested from regional offices of the Department of Tourism. These Excel-based files include localized information such as lesser-known attractions, accredited guides, and community-based tourism efforts not yet published on national platforms. This allows JuanderGO to offer more region-specific, inclusive, and community-aware recommendations for a richer travel experience.
</p>

<!-- Data Acquisition and Storage Architecture -->
<h3> 🧩 Data Acquisition and Storage Architecture </h3> 


<!-- Qdrant Cloud -->
<h3> ☁️ Qdrant Cloud </h3> 
<img src = "https://i.imgur.com/dc4kBEt.png">

<p align="center">
  <img src="https://i.imgur.com/452QwQE.png" width="49%" style="margin-right: 1%;">
  <img src="https://i.imgur.com/avupF4n.png" width="49%">
</p>

<img src = "https://i.imgur.com/jFqOAY5.png">

---

<h2 id="feature-highlights">✨ Feature Highlights </h2>

<img src = "https://i.imgur.com/20bX6cx.png">

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  This section showcases JuanderGO’s key features that work together to deliver a seamless travel planning experience. From smart destination discovery to personalized itinerary building, each component is powered by AI to streamline the user journey.
</p>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  These include: <strong>Intelligent Search</strong> for fast and relevant travel queries, <strong>Agentic AI Agents</strong> for dynamic itinerary generation, a built-in <strong>Chatbot</strong> for conversational support, and <strong>Automated Email Inquire</strong> for sending personalized itineraries directly to your inbox.
</p>

<h3 id="intelligent-search">🔍 Intelligent Search</h3>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
  JuanderGO’s Intelligent Search feature allows users to explore travel data using three different techniques: <strong>Keyword</strong>, <strong>Semantic</strong>, or <strong>Hybrid Search</strong>. Users can search across various categories including attractions, events, accommodations, and more — with results ranked by similarity relevance.
</p>

<h4> Architecture </h4>

<h5> Keyword Seach </h5>

<h5> Semantic Seach </h5>

<h5> Hybrid Seach </h5>

<h4> User Guide </h4>

<ol style="font-size: 16px; line-height: 1.6;">
  <li><strong>Select Search</strong> – Begin by clicking on the search tab in the navigation panel.</li>
  <li><strong>Select a Category</strong> – Choose what you want to search from a list of options like attractions, activities, accommodations, restaurants, travel agencies, tour guides, events, or facts and trivia.</li>
  <li><strong>Select Search Technique</strong> – Choose from <em>Keyword</em>, <em>Semantic</em>, or <em>Hybrid</em> based on how you want the search to interpret your query.</li>
  <li><strong>Enter Search Query</strong> – Type in your desired keyword, phrase, or topic to explore.</li>
  <li><strong>View Results</strong> – The output will display a ranked list of relevant matches, each with a similarity score showing how closely it aligns with your query.</li>
</ol>

<p align="center">
  <img src="https://i.imgur.com/GZrJsay.png" alt="Steps 1 to 3" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Steps 1–3: Selecting search mode, category, and technique.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/ulypi1V.png" alt="Step 4 Input" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Step 4: Typing in your search query.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/GZrJsay.png" alt="Step 5 Results" width="80%" style="border-radius: 12px;">
  <br>
  <em>Step 5: Viewing the ranked results with similarity scores.</em>
</p>


<h3 id="agentic-ai-agents">🤖 Agentic AI Agents</h3>

<img src="https://i.imgur.com/zvOlYaK.png" alt="Agentic AI Agents" />

JuanderGo integrates a collaborative crew of **9** agentic agents, each designed to perform specialized tasks to collectively plan your next big adventure in the Philippines. These agents simulate human-like decision making to deliver highly personalized, context-aware, and efficient travel itineraries.

| #  | Agent               | Purpose                                                                                     |
| ---|---------------------|---------------------------------------------------------------------------------------------|
| 1  | Flight Agent        | Recommends the flights available in accordance to your travel dates and preferences.        |
| 2  | Weather Agent       | Pulls real-time weather data via the Google Weather API to recommend what to pack and expect weather-wise. If live data is unavailable, it uses historical trends to gauge the weather. |
| 3  | Facts and Trivia Agent | Introduces you to the destination’s culture, customs, and quirks. Offers fun facts and essential travel tips to enrich your experience. |
| 4  | Events Agent        | Scans your travel window for festivals, events, or local celebrations, highlighting them for a culturally immersive experience. |
| 5  | Attraction Agent    | Compiles popular landmarks and hidden gems, then uses the Google Distance Matrix API to optimize travel routes. |
| 6  | Activities Agent    | Suggests activities tailored to your interests and travel style, from relaxation to adventure and cultural experiences. |
| 7  | Accommodation Agent | Recommends accredited lodging options based on your destination, ensuring a safe and comfortable stay. |
| 8  | Restaurant Agent    | Recommends accredited dining establishments, tailored to your cravings and dietary restrictions for a great culinary experience. |
| 9  | Itinerary Agent     | Compiles all details from other agents to build a personalized day-by-day itinerary tailored to your preferences. |

<h4> Flight Agent</h4>
<p align="center">
  <img src="" alt="Flight Agent Result" width="70%" style="border-radius: 12px;" />
</p>

<h4> Weather Agent</h4>
<p align="center">
  <img src="https://i.imgur.com/Z73jajy.png" alt="Weather Agent Result" width="70%" style="border-radius: 12px;" />
</p>

<h4> Facts and Trivia Agent</h4>
<p align="center">
  <img src="https://i.imgur.com/s7gLeqL.png" alt="Facts and Trivia Result" width="70%" style="border-radius: 12px;" />
</p>

<h4> Events Agent</h4>
<p align="center">
  <img src="https://i.imgur.com/aOjchSC.png" alt="Event Agent Result" width="70%" style="border-radius: 12px;" />
</p>

<h4> Accommodation and Restaurant Agent</h4>
<p align="center">
  <img src="https://i.imgur.com/FBGE7cE.png" alt="Accommodation and Restaurant Agent Result" width="70%" style="border-radius: 12px;" />
</p>

<h4> Itinerary Agent</h4>
<p align="center">
  <img src="https://i.imgur.com/44eKbiO.png" alt="Itinerary Agent Result" width="70%" style="border-radius: 12px;" />
</p>


<h4> Agents Behavior </h4>

<h4> Architecture </h4>

<h4> User Guide </h4>

<ol style="font-size: 16px; line-height: 1.6;">
  <li><strong>Select Agents</strong> – Navigate to the Agents tab to access the agent interface.</li>
  <li><strong>Input Required Fields</strong> – Fill in all necessary information such as destination, travel dates, interests, and preferences.</li>
  <li><strong>Select Agent to Run</strong> – Choose which specific agent(s) to activate, depending on what information you want generated.</li>
  <li><strong>Submit Request</strong> – Click the submit button to start the agent's execution process.</li>
  <li><strong>Wait for Agent Execution</strong> – The agent will process the data and run background logic to generate tailored outputs.</li>
  <li><strong>View and Download Results</strong> – Once complete, view the generated response and optionally download your itinerary or agent report.</li>
</ol>

<p align="center">
  <img src="https://i.imgur.com/m7rLpja.png" alt="Steps 1 & 2 – Select agents and input details" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Steps 1–2: Selecting agents and entering required fields.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/5eij9ks.png" alt="Steps 3 & 4 – Select and run agent" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Steps 3–4: Choosing an agent and submitting the request.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/PFG90rZ.png" alt="Step 5 – Agent running" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Step 5: Agent execution in progress.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/shbwwE4.png" alt="Step 6 – Results displayed" width="80%" style="border-radius: 12px;">
  <br>
  <em>Step 6: Viewing and downloading the result.</em>
</p>

<h3 id="chatbot">💬 Chatbot</h3>

<h4> User Guide </h4>

<ol style="font-size: 16px; line-height: 1.6;">
  <li><strong>Select Chatbot</strong> – Navigate to the chatbot section in the app interface.</li>
  <li><strong>Input Query</strong> – Type your question, travel concern, or request into the chat input field.</li>
  <li><strong>Wait and See Results</strong> – The chatbot will process your query and return an intelligent response based on its trained data and connected tools.</li>
</ol>

<p align="center">
  <img src="https://i.imgur.com/N0z110X.png" alt="Steps 1 & 2 – Select chatbot and input query" width="80%" style="border-radius: 12px; margin-bottom: 10px;">
  <br>
  <em>Steps 1–2: Accessing the chatbot and entering your question.</em>
</p>

<p align="center">
  <img src="https://i.imgur.com/Lkv5qVK.png" alt="Step 3 – Chatbot response" width="80%" style="border-radius: 12px;">
  <br>
  <em>Step 3: Receiving a contextual response from the chatbot.</em>
</p>

<h3 id="automated-email-inquire">📧 Automated Email Inquiry</h3>

<h4> User Guide </h4>

---

<h2 id="how-to-access-juandergo-online"> 📶 How to Access JuanderGO Online</h2>

<p align="justify" style="font-size: 16px; line-height: 1.6;">
You can access JuanderGO by pressing the button below or by manually entering the link into your browser.
</p>

<p align="center">
  <a href="https://juandergo.aratilismk.com/">
    <img src="https://img.shields.io/badge/-🌏%20JuanderGo-orange?style=for-the-badge" alt="JuanderGo" />
  </a>
</p>

---

<h2 id="how-to-run-juandergo-locally"> 🖥️ How to Run JuanderGO Locally </h2>

---

<h2 id="repository-structure"> 🏗️ Repository Structure </h2>

---

<h2>👨‍💻 Team Details 👨‍💻</h2>

<table align="center" width="100%">
  <tr>
    <!-- Giorgio -->
    <td align="center" width="50%">
      <img src="https://i.imgur.com/X9hmBNp.png" alt="Giorgio Armani Magno" style="border-radius: 50%; width: 120px; height: 120px;"><br><br>
      <strong>Giorgio Armani Magno</strong><br>
      <em>Data Scientist</em><br><br>
      <p align="center">
        <a href="https://github.com/ggiorgioarmanim">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
        </a>
        <a href="https://linkedin.com/in/giorgioarmanimagno">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
        </a>
      </p>
    </td>
    <!-- Rae -->
    <td align="center" width="50%">
      <img src="https://i.imgur.com/xHKeiUq.png" alt="Rae Paulos" style="border-radius: 50%; width: 120px; height: 120px;"><br><br>
      <strong>Rae Paulos</strong><br>
      <em>Computer Science Student</em><br><br>
      <p align="center">
        <a href="https://github.com/rpaulos">
          <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
        </a>
        <a href="https://linkedin.com/in/rae-paulos-8969b5249">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
        </a>
      </p>
    </td>
  </tr>
</table>

<div align="center">
  <img src="https://i.imgur.com/cDW81Uz.png" />
</div>
