GLOBAL GIVING ANDROID APP
=========================

GlobalGiving is a non-profit organization based in the United States that provides a global crowdfunding platform for grassroots charitable projects. Since 2002, more than 402,000 donors on GlobalGiving have raised more than $148 million to support more than 10,650 projects around the world.

There is no mobile app for this crowdfunding platform as of today and we have decided to build one as our codepath project. GlobalGiving provides REST API’s to access and update many of their endpoints. This makes the job of developers easier to contribute to this site.

Core User Stories:
===================

- Stream of Available Projects
  - Shown by default sorted list on Priority

- Filter to help user provide more search options
  - Filter By Category
  - Filter By Theme
  - Filter By Region

- List projects based on user’s location (wifi - coarse)
- Also an option of manually entering the location/region

- Project Detailed View
  - Slide show for Project related Images/media
  - Detailed description of the project
  - Donate Feature to allow user donate to the project

- Share option (Share using Facebook/Twitter)

- Donation View
  - User can donate to the project by providing the needed info
  - Notification once the donation is accepted
  - An option to share the donation made (Share using Facebook/Twitter)

- Share option
  - Using Facebook API to allow the user post/like the project/donation
  - Using Twitter API to tweet the project/donation

- Preferences Dialog to save the App-specific settings
  - Region
  - Theme
  - Campaign

- Local persistence
  - List of Projects loaded recently
  - Project Details with minimal info
  - Preferences

Optional User Stories:		
======================	

- Login API & Backend Service using API to allow user register and login to the App
- Save the User Preferences & Settings in Parse and sync with the local ones
- Google Maps integration to allow the user select a country/region for filtering the Project List View
