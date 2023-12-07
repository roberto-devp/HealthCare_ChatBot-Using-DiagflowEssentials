# HealthCare ChatBot for COVID-19 Vaccination Appointments

During the challenging times of the COVID-19 pandemic, securing vaccination appointments has been a crucial aspect of public health. This project addresses the issue of long queues and difficulties in booking appointments by introducing a HealthCare ChatBot dedicated to facilitating COVID-19 vaccination scheduling.

# How it Works:

1.User Registration: Users provide necessary details for registration.

2.Appointment Scheduling: Seamless booking process with personalized options.

3.Confirmation: Users receive confirmation details for their scheduled appointment.


![WhatsApp Image 2023-12-04 at 12 46 32_56aa28cd](https://github.com/ShaikSameehaTabassum/HealthCare_ChatBot-Using-DiagflowEssentials/assets/83460032/c6f0adf9-ace2-4859-a3c4-c2e7e81d6955)

# Intents in the HealthCare ChatBot Project:
In the HealthCare ChatBot project, intents play a pivotal role in understanding and categorizing the end-user's intentions during a conversation turn. Intents are predefined categories that represent the purpose or goal of a user's input. Here's an overview of the intents defined in this project:

1.Aadhar card:

This intent is designed to capture and handle user inquiries or information related to Aadhar card details. It ensures secure and accurate processing of Aadhar-related queries.

2.Age:

The age intent is responsible for extracting and managing user-provided age information. It plays a crucial role in tailoring the vaccination appointment process based on the user's age group.

3.Approval:

The approval intent deals with user responses indicating consent or approval. It facilitates the confirmation of appointment bookings and ensures a smooth interaction flow.

4.Default fallback intent:

When the ChatBot encounters user input that doesn't match any specific intent, the default fallback intent comes into play. It gracefully handles unexpected queries, guiding users back to the intended conversation flow.

5.Default welcome intent:

The default welcome intent provides a friendly greeting and initiates the conversation with users. It sets the tone for a positive and user-friendly interaction.

6.Denial:

The denial intent captures user responses indicating rejection or disapproval. It is crucial for managing user preferences and decisions during the appointment booking process.

7.Female:

This intent focuses on extracting and managing user-provided gender information when the user identifies as female.

8.Male:

Similar to the female intent, the male intent manages user-provided gender information but specifically for users identifying as male.

9.Names:

The names intent is responsible for recognizing and extracting user-provided names. It ensures accurate personalization during the appointment booking process.

10.Times:

The times intent handles user queries related to appointment scheduling times. It interprets and processes the time preferences specified by the user.

11.Transgender:

This intent is designed to recognize and manage user-provided gender information when the user identifies as transgender. It contributes to the inclusivity of the HealthCare ChatBot.

# How Intents Work:

When a user interacts with the HealthCare ChatBot, the system uses Natural Language Processing (NLP) to match the user's input (end-user expression) to the most relevant intent. This process, known as intent classification, ensures that the ChatBot understands the user's intention and responds appropriately.
![WhatsApp Image 2023-12-04 at 12 47 07_7e8b12ba](https://github.com/ShaikSameehaTabassum/HealthCare_ChatBot-Using-DiagflowEssentials/assets/83460032/02a96465-d748-47c4-8541-e880360a92e8)

# Entities in the HealthCare ChatBot Project:

Entities in the HealthCare ChatBot project are placeholders for important pieces of information extracted from user input. They play a crucial role in capturing specific data such as Aadhar card numbers and user ages. Here are the entities defined in this project:

1.@AADHAR_CARD:

This entity is specifically designed to extract and handle Aadhar card details from user input. It ensures the secure and accurate processing of Aadhar-related information during the conversation.

2.@aadharcard_no:

The @aadharcard_no entity is responsible for extracting Aadhar card numbers provided by the user. It facilitates precise record-keeping and verification during the appointment booking process.

3.@AGE:

The @AGE entity is crucial for extracting and managing user-provided age information. It plays a key role in tailoring the vaccination appointment process based on the user's age group.

4.@under_18:

The @under_18 entity is used to identify users who are under the age of 18. It is particularly important for managing age-specific eligibility criteria during the appointment scheduling process.

# How Entities Work:

Entities work hand-in-hand with intents to enhance the understanding of user input. When a user interacts with the HealthCare ChatBot, entities extract specific pieces of information mentioned in the user's input, making it easier to process and respond appropriately.
![WhatsApp Image 2023-12-04 at 12 47 40_06ea372e](https://github.com/ShaikSameehaTabassum/HealthCare_ChatBot-Using-DiagflowEssentials/assets/83460032/cb640ba8-d053-4566-8807-43089d86a535)
![WhatsApp Image 2023-12-04 at 12 50 11_634e13bc](https://github.com/ShaikSameehaTabassum/HealthCare_ChatBot-Using-DiagflowEssentials/assets/83460032/add6bcc3-d20f-402e-9631-48373a4e9eed)
to see:
https://bot.dialogflow.com/522ba424-6f62-4f6a-a45d-47e376563f60
