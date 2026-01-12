# ML-Projects
🚲 Bike Booking Rush Prediction

This project is inspired by a real experience I had while traveling during the Sankranti holidays.

Living in Hyderabad, traffic is a common challenge, but thanks to the metro, I usually manage my travel well. On that particular day, I left 1.5 hours early to catch my train.
However, it took nearly 25 minutes just to find a Rapido bike ride, even though bike rides are usually the most affordable and convenient option for me as an individual commuter.

I ultimately reached the railway station just in time — the train had already started moving, and with the help of a policeman, I managed to board it while carrying two bags.
Had I missed that train, I would have also missed my connecting flight the same night, which would have completely disrupted my vacation plans.

This incident raised a critical question:

Why can’t ride-booking platforms like Rapido or Uber predict high booking demand in advance and deploy more drivers proactively?

To explore this idea, I designed a machine learning classification model that predicts bike booking rush levels (Low, Medium, High) based on factors such as time, location, weather, holidays, and special occasions.
The goal is to help platforms better manage demand and reduce last-minute delays for users.

🧠 Models Experimented

During the model-building phase, I experimented with multiple classification algorithms:

Logistic Regression
Used as a simple baseline model for multi-class prediction.

Decision Trees & Random Forests
Helped capture basic non-linear booking patterns and feature interactions.

Support Vector Classifier (SVC)
Provided the best balance between accuracy and generalization across unseen data.

✅ Final Model Selected: Support Vector Classifier (SVC)

🔗 Live Demo

👉 Try the Live Model on Hugging Face:
https://huggingface.co/spaces/mrunalrinait/Bike_Rush_Booking_Classifier
