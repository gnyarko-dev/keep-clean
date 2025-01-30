# KeepClean

## Introduction

Hello everyone! Today, I’m excited to introduce **KeepClean**, an innovative waste management and community engagement platform designed to make a lasting impact on both our environment and future flood prevention efforts.

This platform was born from a personal experience. My community faced a devastating flood that destroyed homes, properties, and countless livelihoods. The aftermath highlighted how poor waste management contributes significantly to environmental hazards, including flooding. I realized that we could take action to prevent such disasters in the future by focusing on improving how we manage waste today.

**KeepClean** was built with a clear mission: to keep our communities clean and help prevent future floods by encouraging proper waste disposal. This platform not only provides a way for people to report and collect waste but also rewards them for their efforts, transforming waste management into an engaging and rewarding experience for everyone.

## Features

- **Homepage:** Displays an overview of the platform and its mission.
- **Impact Section:** Shows statistics such as the total waste collected, number of reports submitted, total tokens earned, and total CO2 offset.
- **User Authentication:** Users can sign up or log in using Web3Auth, which supports multiple social media login options.
- **User Profile:** Displays user details, profile settings, and a sign-out option.
- **Report Waste:**
  - Users can report waste by uploading an image.
  - Gemini AI identifies the waste type, estimates its amount, and populates relevant input fields.
  - Users enter the location using Google’s location suggestions.
  - Upon submission, users earn tokens (10 points per report).
  - Submitted reports appear in the **Recent Reports** section.
  - Notifications inform users when they earn points.
- **Collect Waste:**
  - Displays a list of reported waste.
  - Verified status indicates if a waste item has been collected.
  - Users can start waste collection, changing the status to **in progress**.
  - Users must upload an image before verifying the collection.
  - Gemini AI checks if the waste type matches the original report before awarding points.
- **Rewards:** Displays all the rewards earned by the user.
- **Leaderboard:** Highlights the top performers on the platform.

## How to Run Locally

To run KeepClean on your local machine, follow these steps:

### Prerequisites
- Node.js installed (latest LTS version recommended)
- Git installed
- A Web3Auth API key
- Google Maps API key (for location suggestions)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/keepclean.git
   cd keepclean
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env.local` file in the root directory and add the necessary environment variables:
   ```sh
   NEXT_PUBLIC_WEB3AUTH_CLIENT_ID=your_web3auth_client_id
   NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   ```

4. Run the development server:
   ```sh
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Contribution

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push the branch:
   ```sh
   git push origin feature-name
   ```
5. Open a Pull Request and describe your changes.

## License

This project is licensed under the MIT License.