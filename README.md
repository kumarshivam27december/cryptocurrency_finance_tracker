Crypto Finance Tracker

Welcome to the Crypto Finance Tracker, a React-based application designed to help you monitor and track the performance of various cryptocurrencies. This application provides real-time data and historical performance insights, enabling you to make informed decisions about your investments.

   Technologies Used

-   React  : The core framework for building the user interface.
-   Redux  : For state management across the application.
-   Axios  : To make HTTP requests to external APIs.
-   React Router  : For client-side routing and navigation.

   APIs Used

1.   CoinGecko API  
   -   Base URL  :  'https://api.coingecko.com/api/v3 '
   -   Endpoints  : 
     -  '/coins/markets ': For fetching market data.
     -  '/coins/{id} ': For fetching detailed coin information.
     -  '/coins/{id}/market_chart ': For historical market data.

   Getting Started

    Prerequisites

-   Node.js  : Make sure you have Node.js installed (v14 or later is recommended).
-   npm : Node package manager for installing dependencies.

    Installation

1.   Clone the repository:  


   git clone   https://github.com/kumarshivam27december/cryptocurrency_finance_tracker.git

 

2.   Navigate to the project directory:  

  
   cd crypto-finance-tracker


3.   Install dependencies:  


   npm install
     or
   yarn install


    Configuration



1.   Replace placeholders   with your actual API keys.

    Running the Application

To start the development server, use the following command:


npm start



This will start the React application and open it in your default web browser at  'http://localhost:3000 '.

    Building for Production

To create a production build of the application, run:

npm run build





Feel free to submit issues or pull requests. Please make sure to follow the existing code style and include tests for any new features or bug fixes.

 
   Acknowledgments

-   CoinGecko  : For providing free cryptocurrency data.
-   CoinMarketCap  : For additional data and insights (if used).
-   React Community  : For their support and resources in building this application.




