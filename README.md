# Railway Ticket Booking DApp

<h2>Overview</h2>

This project is a decentralized application (DApp) for booking and managing railway tickets on the Ethereum blockchain. The smart contract allows users to book and cancel tickets, while providing real-time availability information. This DApp uses Solidity for the smart contract, and HTML, CSS, and JavaScript for the frontend interface.

<h2>Smart Contract</h2>

<h3>RailwayTicketBooking.sol</h3>

The RailwayTicketBooking smart contract includes the following functionalities:

**Book Ticket:** Allows a user to book a ticket by providing the ticket ID and paying the required ticket price.

**Cancel Ticket:** Allows a user to cancel a booked ticket and receive a refund.

**Check Availability:** Allows anyone to check the number of available tickets.

**Events:** The contract emits TicketBooked and TicketCancelled events for tracking bookings and cancellations.

<h2>Frontend</h2>

<h3>HTML</h3>

The HTML file provides the structure of the web page, including input fields and buttons for booking and canceling tickets, and a section for displaying ticket availability.

<h3>CSS</h3>

The CSS file styles the web page, providing a clean and responsive design. It includes styles for the container, buttons, inputs, and labels.

<h3>JavaScript</h3>

The JavaScript file handles the interaction with the Ethereum blockchain using the Web3.js library. It includes functions to connect to the user's wallet, book tickets, cancel tickets, and check ticket availability.

<h2>Setup</h2>

<h3>Prerequisites</h3>

**Node.js**

**MetaMask** extension for your web browser

<h3>Steps</h3>

**1. Clone the Repository**

**2. Install Dependencies**

**3. Compile and Deploy the Smart Contract**

Use Remix IDE or Truffle to compile and deploy the RailwayTicketBooking.sol contract to the Ethereum blockchain. Make sure to note the contract address.

**4. Update Contract Address and ABI**

In the app.js file, update the contractAddress and contractABI variables with the deployed contract's address and ABI.

**5. Run the Application**

Open the index.html file in your web browser. Make sure your MetaMask extension is connected to the correct network.

<h2>Usage</h2>

**1. Connect Wallet:**

Click the "Connect Wallet" button to connect your MetaMask wallet.

**2. Book Ticket:**

Enter a ticket ID and click the "Book Ticket" button. Confirm the transaction in MetaMask.

**3. Cancel Ticket:**

Enter the ticket ID to cancel and click the "Cancel Ticket" button. Confirm the transaction in MetaMask.

**4. Check Availability:**

Click the "Check Availability" button to see the number of available tickets.

<h2>License</h2>

This project is licensed under the MIT License.
