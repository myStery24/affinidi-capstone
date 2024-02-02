# Affinidi Capstone: Online Store

Welcome to the Affinidi Capstone Project! In this project, we will be leveraging the power of Affinidi Login and Affinidi Vault to enhance the user experience of an online store. By utilizing the tamper-evident, zero-party data stored in the Affinidi Vault, we can streamline the checkout process and eliminate the hassle of lengthy form-filling.

## Project Overview

In the [previous quests](https://github.com/myStery24/affinidi) of the Affinidi Campaign, you gained insights into how [Affinidi Login](https://portal.affinidi.com/login) and [Affinidi Vault](https://docs.affinidi.com/docs/affinidi-vault/) operate. Now, it's time to apply that knowledge and create a fully functional online store. The key features of our online store include:

- **User Authentication:** Users will log in using Affinidi Login, ensuring a secure and seamless authentication process.

- **Cart Management:** Users can add items to their cart while enjoying a hassle-free shopping experience.

- **Automatic Form Filling:** During checkout, Affinidi Login will request necessary data points from the user's vault, automatically populating their shipping information.

## How It Works

1. **User Registration/Login:**
   - Users will log in using Affinidi, ensuring a secure authentication process.
   - If they are new users, they can create an account with Affinidi Login.

2. **Shopping Experience:**
   - Users can browse through the online store, add items to their cart, and manage their shopping preferences.

3. **Checkout Process:**
   - When ready to checkout, users will log in again with Affinidi.
   - Affinidi Login will request specific data points from the user's vault.

4. **Automatic Form Filling:**
   - With the user's consent, the required data points will be used to automatically fill in shipping information.

## Getting Started

Follow these steps to set up and run the Affinidi Online Store:

1. Clone the repository:

   ```bash
   git clone https://github.com/myStery24/affinidi-capstone.git
   ```

2. Access the project directory and install dependencies:

   ```bash
   cd affinidi-capstone
   npm install
   ```

3. Change directory to the server-app directory:

   ```bash
   cd server-app
   npm install
   ```

4. Configure Affinidi:
- Set up your Affinidi credentials and integrate Affinidi Login and Affinidi Vault into the project.

5. Start the server and run the project:
- Open a terminal, ensure you are in the server-app directory, and enter the following command:
 
    ```bash
    npm start
    ```
    - Terminal should display 'Server listening on 3001'.
- Open another terminal, ensure you are in the affinidi-capstone directory, and enter the following command:
    ```bash
    npm start
    ```
    - Your default browser will open [http://localhost:3000](http://localhost:3000) automatically.

## Technologies Used

- React.js
- Affinidi Login
- Affinidi Vault
- Node.js
- Express.js