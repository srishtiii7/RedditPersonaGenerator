# RedditPersonaGenerator
 A Reddit User Persona Generator pipeline that extracts user data, generates detailed personas using LLMs, and creates beautiful visual persona cards with avatars in a modern columnar layout.
----
## Features

- ✅ Extract posts & comments from Reddit profiles (via PRAW)
- ✅ Analyze and summarize user behavior using LLaMA 3 via Groq API
- ✅ Automatically infer:
  - Name
  - Age
  - Occupation
  - Interests
  - Motivations
  - Habits
  - Frustrations
  - Personality
  - Goals
- ✅ Generate a `.txt` file with citations
- ✅ Create a **visual persona card (.png)** including:
  - Avatar
  - Columnar persona layout
  - Metadata and Reddit activity stats

## Setup
Create a .env file in the root directory
 REDDIT_CLIENT_ID=your_reddit_client_id
 REDDIT_CLIENT_SECRET=your_reddit_client_secret
 REDDIT_USER_AGENT=your_user_agent
 GROQ_API_KEY=your_groq_api_key

Clone the repository and run the python file

## Output
<img width="1161" height="429" alt="image" src="https://github.com/user-attachments/assets/1d78af92-b90a-42cc-b7ef-c961964f78eb" />

