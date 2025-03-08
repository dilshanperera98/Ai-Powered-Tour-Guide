# Ai-Powered-Tour-Guide

Landmark Detection (Google Vision API):

The Google Cloud Vision API is used to detect landmarks in images. It processes the uploaded image (like a photo taken by the user) and returns details about any recognized landmark(s).
The image is encoded into base64 and sent to the Google Vision API via an HTTP request, which returns information such as the name or description of the landmark.
The code captures this output, extracts the most relevant landmark, and returns it to the user.
Use case: The system can automatically identify famous landmarks from a photo that the user takes (e.g., Colosseum, Eiffel Tower).

Historical Description (OpenAI GPT-4):

Once a landmark is detected, the name is passed to the OpenAI GPT-4 API to generate a short historical description about the landmark.
You’ve set up a conversational system where GPT-4 is prompted to provide context, history, and interesting facts about the landmark, enriching the experience for the user.
Use case: After identifying a landmark like the Colosseum, the system fetches historical insights and delivers them as a conversational response, providing tourists with educational content.
      
Flow:
Step 1: User uploads or takes a picture of a landmark.
Step 2: The image is analyzed by the Google Vision API to detect and recognize any landmarks.
Step 3: The detected landmark’s name is sent to OpenAI GPT-4, which returns a historical description.
Step 4: The system presents both the detected landmark and the historical description to the user.
Advantages:
User-Friendly: With just an image, users can receive automatic information about landmarks.
Real-Time Knowledge: Offers dynamic, up-to-date historical facts.
Engagement: Interactive learning by providing detailed, human-like descriptions powered by GPT-4. 
