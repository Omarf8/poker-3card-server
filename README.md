# 3-Card Poker Server

This repository contains the backend server for a multi-client 3-Card Poker application. Developed in Java, the server manages the game state, coordinates player communication, and enforces game rules via a dedicated network protocol.

## Technical Highlights
* **TCP/IP Network:** **Java Sockets** were used to implement a reliable connection that handles multiple concurrent client connections.
* **JavaFX GUI:** Developed a server-side dashboard using **FXML** for layout and **CSS** for styling in order to monitor player activity.
* **Game Logic:** Refined core poker algorithms, including deck shuffling, card dealing, and hand-ranking logic to determine winners.
* **Concurrency Management:** Used multi-threading to handle individual client streams, ensuring the server remains responsive as players join and leave.

## 📸 Screenshots
### Server Dashboard
This server dashboard provides server initialization, built with FXML and custom CSS.

<img width="998" height="688" alt="Start Server Screen" src="https://github.com/user-attachments/assets/7555440f-a661-44e6-8193-6e8457b81ec2" />

### Real-Time Event Log
The server log tracks client connections, hand outcomes, game state transitions across the TCP network, and other relevant game status.

<img width="998" height="688" alt="Server Log" src="https://github.com/user-attachments/assets/8779c3ab-40a3-45e2-b2a4-32acc6397013" />



