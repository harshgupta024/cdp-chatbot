Support Agent Chatbot for CDP

Objective

Develop a chatbot that answers "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot should extract relevant information from official documentation to guide users on performing tasks or achieving specific outcomes within each platform.

Data Sources

Segment Documentation: Segment Docs

mParticle Documentation: mParticle Docs

Lytics Documentation: Lytics Docs

Zeotap Documentation: Zeotap Docs

Core Functionalities

1. Answer "How-to" Questions

Understand and respond to user queries on specific tasks and features within each CDP.

Example questions:

"How do I set up a new source in Segment?"

"How can I create a user profile in mParticle?"

"How do I build an audience segment in Lytics?"

"How can I integrate my data with Zeotap?"

2. Extract Information from Documentation

Retrieve relevant information from the provided documentation to answer user questions.

Navigate through the documentation, identify relevant sections, and extract necessary instructions or steps.

3. Handle Variations in Questions

Ensure the chatbot can process and handle variations in question phrasing.

Prevent breakdown on extremely long queries.

Handle irrelevant questions gracefully (e.g., "Which movie is getting released this week?").

Bonus Features

Cross-CDP Comparisons

Provide comparisons between different CDPs based on user queries.

Example question: "How does Segment's audience creation process compare to Lytics'?"

Advanced "How-to" Questions

Handle complex platform-specific queries.

Provide guidance on advanced configurations, integrations, or use cases.

Evaluation Criteria

Accuracy and completeness of responses.

Code quality and build.

Handling of variations in question phrasing and terminology.

Implementation of bonus features (cross-CDP comparisons, advanced questions).

Overall user experience and chatbot interaction.

Implementation Notes

You can use any NLP libraries or frameworks to build the chatbot.

Instead of NLP, a simple document indexer can be used.

The chatbot can be implemented as a web application using any technology.

The focus of this project is software engineering rather than model building.

Setup & Installation

Clone the repository:

git clone <repo-url>
cd Support-Agent-Chatbot-for-CDP

Install dependencies:

pip install -r requirements.txt  # If using Python

Run the chatbot application:

python app.py  # Example command
