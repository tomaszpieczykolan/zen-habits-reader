# README #

Zen Breath is a convenient and easy to use client for the popular blog Zen Habits that I’ve put on the iOS App Store.

The application uses Core Data to store all posts on the blog and some metadata such as whether or not you have read the post. The app fetches all posts from the website using an HTML parsing algorithm that I wrote in order to build model objects from HTML table rows. Each day it performs a background fetch to check if new posts have been released and sends a notification to the user if a new post was found.

![Screenshot 1](https://cloud.githubusercontent.com/assets/10298140/12490010/0a5be4f0-c07c-11e5-9ebe-9bdf8c13f2ef.jpg)
![Screenshot 2](https://cloud.githubusercontent.com/assets/10298140/12490009/078d8940-c07c-11e5-89be-653bbe3d9cae.jpg)
