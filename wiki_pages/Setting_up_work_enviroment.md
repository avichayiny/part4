Setting Up Work Environment (Working on Linux)
Step 1: Run the CPP Server on Your Computer
![הרצת שרת cpp](https://github.com/user-attachments/assets/fc50ce38-d110-45f3-b568-8733fdc71ca1)



Open your terminal (on your IDE)

Ensure you have the latest version of Node.js installed. You can check the version using:

node -v
Create a build directory and navigate into it:

mkdir build
cd build
Generate the makefiles using CMake:

cmake ..
Compile the project:

make
Run the server:

./BloomFilter
Screenshot at 2024-05-22 17-50-57

Step 2: Run the JS Server
Ensure MongoDB is installed and running on your computer. If MongoDB is not installed, follow the official MongoDB installation guide.

Clone the JS server repository from Git (production part 4 branch), or download it as Zip file and extract it:

Screenshot at 2024-05-22 17-56-10

Open your terminal (on your IDE)

Install the required dependencies:

npm install
Ensure you have the latest version of Node.js installed. You can check the version using:

node -v
Start the server:

npm start
Screenshot at 2024-05-22 18-57-15

Open your web browser and go to http://localhost:12345. The web app should be running.

Screenshot at 2024-05-22 18-09-12

Step 3: Run the Android App
Clone the Android app repository from Git (production part 4 branch), or download it as a Zip file and extract it:

Open Android Studio on your computer.

Import the cloned Android app project into Android Studio.

Set up an emulator or connect a smartphone of your choice to run the app.

Build and run the app using Android Studio.
