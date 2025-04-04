# Web Development Project 5 - *Data-Dashboard*

Submitted by: **Dennis Shlaih**

This web app: **This React-based data dashboard is a book discovery application that fetches and displays books using the OpenLibrary API. Users can browse a dynamically updated list of books, search for specific titles, and filter books by category. The dashboard also includes key summary statistics about the data.

Time spent: **8** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] **The site has a dashboard displaying a list of data fetched using an API call**
  - The dashboard should display at least 10 unique items, one per row
  - The dashboard includes at least two features in each row
- [X] **`useEffect` React hook and `async`/`await` are used**
- [X] **The app dashboard includes at least three summary statistics about the data** 
  - The app dashboard includes at least three summary statistics about the data, such as:
    - [X] *Total number of books*
    - [X] *Most common author*
    - [X] *Average title length*
- [X] **A search bar allows the user to search for an item in the fetched data**
  - The search bar **correctly** filters items in the list, only displaying items matching the search query
  - The list of results dynamically updates as the user types into the search bar
- [X] **An additional filter allows the user to restrict displayed items by specified categories**
  - The filter restricts items in the list using a **different attribute** than the search bar 
  - The filter **correctly** filters items in the list, only displaying items matching the filter attribute in the dashboard
  - The dashboard list dynamically updates as the user adjusts the filter

The following **optional** features are implemented:

- [ ] Multiple filters can be applied simultaneously
- [ ] Filters use different input types
  - e.g., as a text input, a dropdown or radio selection, and/or a slider
- [ ] The user can enter specific bounds for filter values

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Data-Dashboard Walkthrough](https://github.com/user-attachments/assets/c0962ad9-a901-4b15-b5c6-0d8c0ffcdb03)

GIF created with Microsoft Clipchamp  

## Challenges

- [X]  Initially, the book list wasn't rendering as expected, which was caused by issues with fetching data from the OpenLibrary API and filtering it correctly. Debugging the API response and ensuring the state was properly updated helped resolve this issue.
- [X] Making sure the useEffect hook worked correctly to fetch books dynamically based on category selection was difficult. There were issues with dependencies and re-fetching data when the category changed, which required careful state management.
- [X] Making the UI visually appealing, particularly aligning elements like the navbar, statistics, and book list, was also a challenge.

## License

    Copyright [2025] [Dennis Shlaih]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
