# SHARE ME

## Description

SHARE ME is a web application that allows users to find and share wallpapers with others. It also features a complex search and navigation system that provides personalized search results based on the user's search history. Users can subscribe monthly to access additional features.

## Installation

To install this project locally, follow these steps:

Clone the repository to your local machine:
bash
git clone https://github.com/yourusername/share-me.git
Navigate to the project directory:
bash
Copy code
cd share-me
Install the required dependencies:
bash
Copy code
npm install
Set up your Sanity account and create a new project.

Navigate to your project's settings in the Sanity dashboard and copy the projectId and dataset values.

Create a new file named .env.development in the root of the project directory, and add the following lines:

bash
Copy code
SANITY_STUDIO_PROJECT_URL=http://localhost:3000
SANITY_STUDIO_PREVIEW_SECRET=<your_preview_secret>
SANITY_STUDIO_API_PROJECT_ID=<your_project_id>
SANITY_STUDIO_API_DATASET=<your_dataset>
Run the following command to start the development server:
bash
Copy code
npm run start
Open your web browser and navigate to http://localhost:3000.
Technologies Used
This project was built using:

React
Tailwind CSS
Sanity
Contribution
If you would like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch with your changes:

bash
Copy code
git checkout -b my-feature-branch
Make your changes and commit them:
bash
Copy code
git commit -m "Add some new feature"
Push your changes to your fork:
bash
Copy code
git push origin my-feature-branch
Create a new pull request.
License
This project is licensed under the MIT License.
