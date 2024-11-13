# SpoilSaver's Submission for Google's Women Techmakers She Builds AI Hackathon
SpoilSaver is an AI-driven mobile app that makes sustainable food management simple and effective. By reducing food waste, it also helps users save money through features like Smart Storage Recommendations, Spoiler Alerts, and Grocery Lists.

### Advancing Gender Equality
As a woman-led company, SpoilSaver champions gender equality by promoting women’s representation in technology and entrepreneurship. Women remain underrepresented in fields like tech and engineering, with only around 25% of computing jobs held by women in the U.S. (National Center for Women & Information Technology). By creating and leading SpoilSaver, we actively address this gender gap, offering a powerful example for other women considering careers in STEM.

Our team demonstrates that women can be leaders in innovation, combining our electrical, software, computer engineering and data science expertise with a commitment to sustainability. We aim to inspire the next generation of women entrepreneurs and tech leaders by showcasing female leadership in tackling global challenges. Additionally, by prioritizing sustainability and eco-conscious living, SpoilSaver aligns with our broader mission: creating a world where both women and the planet can thrive.

## What does SpoilSaver do?
SpoilSaver is an AI-powered mobile app designed to help individuals reduce food waste and save money. It offers a suite of features to help users manage their food more effectively. With Smart Storage Recommendations, Spoiler Alerts, and Grocery Lists, SpoilSaver helps users track their food inventory and get notified before items expire, ensuring they can make the most of what they’ve bought. The app uses AI to estimate expiration dates and recommend where to store certain foods to help them last longer, and giving users a clear picture of their food’s freshness by providing real-time insights helping them make smarter decisions about what to eat next.

## How we built it
We built SpoilSaver using a MERN stack (MongoDB, Express, React, Node.js) alongside Expo and React Native for a powerful, cross-platform mobile experience. Our goal was to create an app that not only helps reduce food waste but also delivers a seamless and engaging user experience.

### Frontend (Expo, React Native)
To ensure that SpoilSaver was responsive and accessible across both iOS and Android, we used Expo and React Native. Expo simplified our development process, allowing us to focus on building intuitive features such as:

- Smart Storage Recommendations: Helping users store food in the most effective way.
- Spoiler Alerts: Alerting users when food is nearing expiration.
- Grocery Lists: Allowing users to track what they need and what they have.

These features give users the power to manage their food efficiently, ensuring they reduce waste and maximize the value of what they buy.

### Backend (Node.js, Express, MongoDB)
On the backend, we used Node.js and Express for handling API requests and app logic, while MongoDB served as the database to store user data like food inventories, expiration dates, and other related information. This infrastructure ensured seamless syncing of data, allowing users to access updated information from multiple devices.

### AI Integration with Gemini-Pro
To take our app's capabilities to the next level, we integrated Google's Gemini-Pro AI model, which played a central role in generating personalized food details that are leveraged throughout the app; helping us to create estimated expiration date predictions and made smart suggestions for food storage and use. 

The AI model provided:

- Storage Locations: Gemini-Pro analyzes food items and suggests optimal storage locations (e.g., pantry, counter, fridge, or freezer) based on their type.
- Storage Recommendations: The model provides commonly unknown tips to help prolong the freshness of food items; such as keeping apples away from bananas to prevent rapid ripening or storing leafy greens with a damp paper towel.
- Expiration Date Estimates: The model predicts expiration dates for various food items, helping users stay ahead of potential waste.

# Testing Instructions
