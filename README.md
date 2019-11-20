# Watson-Assistant-Restaurant-reservation
This is a simple dialogue skill for taking restaurant reservation by Watson Assistant. This skill can be imported to your Watson 
Assistant Instance in the following steps:

## Prerequisites

1. Sign up for an IBM Cloud account.
2. Download the IBM Cloud CLI.
 - Create an instance of the Watson Assistant service and get your credentials:
 - Go to the Watson Assistant page in the IBM Cloud Catalog.
 - Log in to your IBM Cloud account.
 - Click Create.


![image](https://user-images.githubusercontent.com/39076220/69197167-b56cd180-0afe-11ea-963d-5e0300be4312.png)

## Choose to add new skill

![image](https://user-images.githubusercontent.com/39076220/69197614-f0bbd000-0aff-11ea-952e-82ff7df22b0a.png)
## Import skill as JSON file

![image](https://user-images.githubusercontent.com/39076220/69197640-092bea80-0b00-11ea-92ba-0b909ece16bc.png)

## Create Intents
When you open the My first skill, you land on the Intents page.
Intents are a set of sentences that have similar meaning and inquire a certain feedback from the Assistant.
In this case my intents include Cancellation, Greeting, Reservation and Reschedule.

![image](https://user-images.githubusercontent.com/39076220/69197217-d6cdbd80-0afe-11ea-8a9d-b7649f43e9ba.png)

## Create Entities 
Entities are objects with assigned values that can be called inside dialog. In this case, my entites include Location(with 2 values), Confirmation number(with 2 values but can be expanded to many) and Confirmation in form of Yes/No response.

![image](https://user-images.githubusercontent.com/39076220/69197242-e0efbc00-0afe-11ea-9621-e57aec931a2f.png)

## System Entities

Watson provided a lot of prebuilt entities such as time, person... such that you can assign these entities to variables. 
These variables will be filled when you input data such as your name, location as seen in the sample run

![image](https://user-images.githubusercontent.com/39076220/69197282-f49b2280-0afe-11ea-88b5-8260c5e2adc6.png)

## Dialog Tree
The following is the dialog tree build from established intents and entities. 

![image](https://user-images.githubusercontent.com/39076220/69197337-0d0b3d00-0aff-11ea-9dca-7a32940000c2.png)

## Sample Run

![image](https://user-images.githubusercontent.com/39076220/69197441-52c80580-0aff-11ea-8e7a-fb6a16e801c2.png)

![image](https://user-images.githubusercontent.com/39076220/69197453-5c516d80-0aff-11ea-8729-afced0f1b6a4.png)
