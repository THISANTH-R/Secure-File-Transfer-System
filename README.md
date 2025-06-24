🔐 Secure File Transfer System with Merkle Tree
This project provides a robust and secure file transfer system implemented in Python. It enables encrypted communication between a client and server for uploading, downloading, and displaying files, while ensuring data integrity through Merkle Tree verification. A user-friendly interface is built using Streamlit for seamless interaction.

🚀 Key Features
🔒 Secure Communication
Uses sockets for reliable client-server interaction.

Implements Fernet symmetric encryption to ensure confidentiality during file transfer.

🌳 Data Integrity with Merkle Tree
Files are divided into chunks, and a Merkle Tree is constructed for each.

Guarantees tamper-proof and corruption-free file transfers by verifying data integrity.

🖥️ User-Friendly Streamlit Interface
Intuitive web-based UI powered by Streamlit.

Enables users to upload, download, and view available files easily.

📜 Logging & Error Handling
Integrated logging mechanism for tracking operations and debugging.

Robust error handling to gracefully manage unexpected events.

🗂️ Project Structure
File	Description
client.py	Handles client-side logic and user interactions via Streamlit.
server.py	Manages server-side operations, connections, and Merkle Tree validation.
logs.csv	Stores logs of events, including timestamps and file transfer status.
requirements.txt	Lists all Python dependencies needed for the project.

⚙️ How to Run
Clone the repository

git clone <your-repo-link>
cd Secure-File-Transfer and split terminal one for client side another for server side then.....
cd code/client-side(client terminal)
cd code/server-side(server terminal)


INSTALL DEPENDENCIES:

pip install -r requirements.txt


RUN THE SERVER:

python server.py or  streamlit run server.py


LAUNCH THE CLIENT :

streamlit run client.py



Now you can use the web interface to securely upload, download, and view files.

🖼️ Screenshots
Screenshots of the web interface are available in the screenshots/ folder. (Ensure the folder exists and contains visuals of the UI.)

📌 Notes
This project is suitable for educational and proof-of-concept use.

Additional enhancements such as RSA encryption, access control, or HTTPS can be integrated for production environments.

Thank you for exploring this project!
For questions or contributions, feel free to open an issue or submit a pull request.