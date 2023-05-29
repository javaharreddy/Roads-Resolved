# Roads Resolved
## Road Complaints - Raise Issues with Road Problems

This project is a web application that allows users to raise complaints or issues related to road problems. Users can upload images of road issues, provide descriptions, and submit their complaints.

## Features

- Upload and preview images of road problems.
- Enter a description of the problem.
- Automatically retrieve the user's location using geolocation.
- Save image, description, location, and timestamp to Firebase Firestore.
- Display a message confirming the complaint submission.

## Technologies Used

- HTML
- CSS
- JavaScript
- Firebase (Firebase Storage, Firebase Firestore)
- Google Maps API

## Setup

1. Clone the repository or download the code.
2. Open the `index.html` file in a web browser.
3. Ensure an internet connection is available for Firebase and Google Maps API integration.

## How to Use

1. Choose an image file by clicking the "Choose File" button.
2. Enter a description of the road problem in the text area.
3. Click the "Raise Complaint" button to submit the complaint.
4. The image will be uploaded to Firebase Storage, and the image preview will be displayed.
5. The user's location will be retrieved (if geolocation is supported), and the image, description, location, and timestamp will be saved to Firebase Firestore.
6. A message confirming the complaint submission will be displayed.


