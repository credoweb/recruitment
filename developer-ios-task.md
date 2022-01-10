
## IOS Development Task

We at CredoWeb are always trying to improve the look and feel of our platform and a great IOS Developer would help us bring that better experience to the end user.
Your task is to create a very simple news app, consisting of 2 screens: 

![image](https://user-images.githubusercontent.com/4658634/141983981-fb465efe-ca25-42b9-81fc-a1c22109231c.png)

### Resources
- Create a free account at https://currentsapi.services/ to acquire your api key
Use https://api.currentsapi.services/v1/search as end point for your application
- request parameters: language=en, page_number, apiKey (or you can use “Authorization” header)

### Screens
- News List Screen:
  - Title
  - Image - the api provides a rectangular one. You need to display it as center cropped square image
  - Timestamp - Requirements for the timestamp are:
    News older than 24 hours should display a simple date, e.g. “12 November”
    For newer news you should display the time since it was published, e.g. “less than a minute ago”, “2 hours ago”, etc. 
  - The screen should have pull to refresh implemented
  - When an item is clicked it should load the second screen
  - Infinite scrolling (loading in more episodes as you scroll).
- News Details Screen:
  - The full image provided by the api (no cropping this time)
  - Title
  - Tags (“category” array from the api)
  - Description
  - Ellipsized source url, redirecting the user to the browser when clicked


If you feel like you want to show us what you're are really capable of, here is a list of potential enhancements that we have come up with. You can always go the extra mile and do not limit yourself to it if you think of any other possible feature enhancement that you want to include in your submission.

- A search functionality based on news title.
