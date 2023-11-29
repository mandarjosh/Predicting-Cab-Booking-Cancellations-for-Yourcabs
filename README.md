####YourCabs Cab Booking Cancellation Prediction

Overview -
This project aims to improve customer service for YourCabs.com, a cab company in Bangalore, by predicting booking cancellations due to car unavailability. The challenge is to create a predictive model to classify new bookings as either cancelled (1) or not cancelled (0) based on various features.

Dataset -
The dataset is distributed into three parts based on the "travel_type_id." There are three travel type IDs, and separate machine learning models are created for each. The dataset includes various features such as booking details, customer information, and geographical data.

Columns Details -
id: Booking ID
user_id: Customer ID (based on mobile number)
vehicle_model_id: Vehicle model type
package_id: Type of package (e.g., 4hrs & 40kms, 8hrs & 80kms)
travel_type_id: Type of travel (long distance, point to point, hourly rental)
... (other columns as described in the project overview)
Machine Learning Models
Three machine learning models have been created based on the travel type ID. The models include decision tree, random forest, SVM, and bagging classifiers. Data manipulation and balancing techniques, such as RandomOverSampler and RandomUnderSampler, have been employed to enhance model performance.

Contributing -
Feel free to contribute to the project by opening issues or submitting pull requests.

License -
This project is licensed under the MIT License.
