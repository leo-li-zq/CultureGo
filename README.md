# CultureGo
An AI-driven cultural travel exploration assistant using locally deployed LLMs and real-time APIs.



CultureGo: Intelligent Cultural Exploration Assistant

CultureGo is an AI-driven travel consultant designed to bridge the gap between Large Language Models (LLMs) and real-world dynamic data. By implementing custom intent-routing logic, the system provides users with deep cultural insights, real-time weather analytics, and precise financial exchange rates for global destinations.

Core Features
Dynamic Intent Routing: Implements a logic-based router that classifies unstructured user queries into specific functional paths (e.g., Trip Planning, Weather, Currency, or Etiquette), ensuring high response precision.
Physics-Driven Rigor: Developed with a "physical modeling mind," treating API data as experimental inputs that require strict cleaning and structural validation before being synthesized by the LLM.

Multi-Source API Integration:
Serper (Google Search): Automated visual mapping and site scouting.
OpenWeather: Fetching real-time meteorological parameters.
Frankfurter: Performing precise financial calculations and currency conversions.
Magazine-Style UI: A responsive web interface featuring Markdown rendering and automated Word Document Export for offline travel planning.

Tech Stack
Frontend: HTML5, CSS3 (Glassmorphism UI), JavaScript (ES6+).
AI Backend: Locally deployed Qwen-VL-8B via LM Studio.
Deployment: ngrok for secure local-to-cloud tunneling and API exposure.
Documentation: LaTeX (for technical reporting) and Markdown.

System Architecture
User Input: Receives natural language queries.
Intent Classification: The LLM acts as a router to extract metadata (City, Target Currency) and determine the required toolset.
Data Acquisition: Asynchronous calls to RESTful APIs provide the "ground truth" data.
Content Synthesis: The model synthesizes raw data into a cohesive, culturally-aware travel narrative.

Getting Started
Clone the Repository:
"git clone https://github.com/your-username/CultureGo.git"

Configure API Keys: Locate the constants in index.html and replace placeholders with your credentials:
const WEATHER_API_KEY = 'YOUR_OPENWEATHER_KEY';
const SERPER_API_KEY = 'YOUR_SERPER_KEY';
Local Execution: Open index.html in any modern web browser or host via a local server (e.g., Live Server).

Motivation
As an Applied Physics student minoring in AI and Data Analytics at The Hong Kong Polytechnic University, I am fascinated by the intersection of deterministic systems and stochastic language models. This project serves as a practical application of my academic training, demonstrating how rigorous system design can enhance the reliability and utility of generative AI in complex, real-world scenarios.
