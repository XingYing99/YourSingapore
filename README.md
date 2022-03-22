# Yoursingapore


## Your Singapore aims to complement the government’s SingapoRediscovers campaign — in a bid to boost local tourism, thereby helping the AER sector tide past this pandemic. While we aim to encourage Singaporeans to be out and about, we do recognise that COVID-19 has not subsided entirely. Your Singapore will be made with civic-responsibility in mind and will constantly remind users about the need to abide by COVID-19 guidelines. As COVID-19 measures change, the website would be updated to reflect the latest measures laid out by the government. 

### Main User Story
As a merchant, I would like to be able to promote my attraction during expected periods of low capacity for free, allowing me to earn sufficient revenue to tide across COVID-19 without violating safe-distancing guidelines. 

As a local resident, I would like to have a quick and convenient planning tool to plan outings in Singapore — especially since many attractions have different guidelines and prices in light of COVID-19. 

### Users and Benefits
The main users of the website are local tourist attraction owners and Singaporeans. 

The primary beneficiaries of the new website are:
1.	Local tourist attractions
Additional, free platform to reach out to more locals, helping merchants to bring in more revenue. This aids merchants in tiding through the ongoing recession
Merchants can easily update their attraction details such as changes in promotions prices or operating hours, especially since operating conditions are changing frequently due to COVID-19
Merchants can promote their attraction during periods of low-capacity, allowing them to bring in revenue during lull periods

2.	Singaporeans
Informed about Attractions

● Free platform
● Convenient platform to view all ongoing promotions at local attractions
● Easily filter through attractions to suit their personal tastes, preferences and budgets
● Ease of Planning Outings
	
● Can conveniently view nearby eateries, including travelling information
● Ability to plan activities according to the predicted weather
● Able to have a quick overview of the planned itinerary
● Able to easily share itinerary with family and friends
 
3.	Local F&B outlets
While F&B outlets are not our main users, they would be a key beneficiary. In a bid to provide convenience to our users, we would be providing them with a list of eateries around the proximity of places of interest. This would in turn, help to boost business for local F&B outlets.




### General Pages

#### Header.vue
This is the main header used across most of the webpages. Other than the name of our website, it provides users with 2 main functions:


#### Home.vue
This is the landing page of our website. Both users and merchants will start their journey from this page. Users will be prompted to select the start button to start exploring local attractions while merchants can click on the merchant button to be directed to the merchant-side of the webpage. 


![image](https://user-images.githubusercontent.com/71431944/159393020-89f8c047-06df-4af5-9ec4-a5d8b6076c6e.png)


### User Side
#### VisitDate.vue
This page provides an interface for users to select their preferred date of visit. 

![image](https://user-images.githubusercontent.com/71431944/159393308-ed8ee65d-e59c-492b-8db3-67cc262e8673.png)



After selecting a date, users can select their preferred location.
![image](https://user-images.githubusercontent.com/71431944/159393761-e679de53-33af-4932-80ce-08b5b15009ac.png)

#### Reminder.vue 
While promoting local attractions, there is also a need to minimise the risks of a resurgence in COVID-19 cases. As such, YourSingapore would promote civic-responsibility, reminding Singaporeans to abide by safe-distancing measures through a Reminder Page.

![image](https://user-images.githubusercontent.com/71431944/159393972-282c8864-29d3-469f-b020-365630055a1e.png)

#### ActivityList.vue
This page displays a list of attractions, filtered based on the user’s selected date and location.
![image](https://user-images.githubusercontent.com/71431944/159394018-d5080e28-5c84-4fbe-948c-f3bac9241c03.png)



#### ActivityDetails.vue
Each attraction has an activity details page, displaying key attraction-specific information.

![image](https://user-images.githubusercontent.com/71431944/159394147-2269d03a-61b0-4bf4-9afb-d4132fce1bd1.png)




#### Eateries.vue
This page allows users to view eateries in the vicinity of an attraction.

![image](https://user-images.githubusercontent.com/71431944/159394277-09a3d0a9-1294-4969-ae27-58ea4b637506.png)



#### Planner.vue
The planner page providers users with a quick overview of their planned itinerary. 
![image](https://user-images.githubusercontent.com/71431944/159394338-9dd32c88-92ee-4957-807c-b1693c890628.png)



### Merchant Side
This section details the merchant-side page of the website, including the registration of merchants, editing of attraction details, bumping of attractions as well as a dashboard page for merchants to view user statistics for their attraction. 
(To test merchant accounts, use the password “123456”. The specific email account names can be found under the authentication page of our Firebase project)

#### Login.vue
Under the merchant tab, merchants are directed to a login page whereby merchants can either login to an existing account or register a new account.
![image](https://user-images.githubusercontent.com/71431944/159394495-a0442674-1f32-49c8-a100-63a87c6e6b24.png)

### Register.vue
Registration page for new merchants. 

![image](https://user-images.githubusercontent.com/71431944/159394540-577982bf-9bed-433a-b906-3df11049599e.png)

#### Merchant Form
Upon registration, merchants are directed to a page to fill in the relevant attraction details. 

![image](https://user-images.githubusercontent.com/71431944/159394628-fe79add1-2ccf-4487-8c8b-50daab99c998.png)

#### Verification Page
After attraction owners have filled up all the relevant attraction details, they would receive a confirmation message that their registration details have been successfully submitted and is pending verification. 

![image](https://user-images.githubusercontent.com/71431944/159394674-b6132e77-9647-4a7d-95db-41466d038a6d.png)

#### Master Account
A master account (email: master@gmail.com, password: 123456) for the YourSingapore team to process the verification of merchants and attractions. 

![image](https://user-images.githubusercontent.com/71431944/159394731-c532e8ba-4c62-4254-ad31-1052f9da08c7.png)


#### Edit_details_merchant.vue
Upon successful login of a merchant, the merchant is directed to his attraction page whereby all the attraction details he has previously keyed in is stored and can be edited.

![image](https://user-images.githubusercontent.com/71431944/159394799-53489497-2cc2-425b-823c-3d80b764a167.png)


#### End

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
