/*
 * Twilio Call Scheduler
 *
 * Overview:
 * The Twilio Call Scheduler is a Windows application that automates making phone calls using Twilio's API. 
 * Users can input up to 8 Twilio phone numbers and a target phone number, and the application will manage 
 * the call scheduling over a defined period (up to 10 hours). Calls are spaced randomly within each hour, 
 * and users can save and load Twilio numbers via a JSON file.
 *
 * Features:
 * - Schedule 2 to 3 automated calls per hour.
 * - User-friendly GUI built with Tkinter.
 * - Save and load Twilio numbers from a JSON file (`twilio_numbers.json`) stored in the local directory.
 * - Fully packaged as a Windows executable, no need to install Python.
 *
 * Requirements:
 * - Windows OS (for running the executable).
 * - Internet connection (for Twilio API usage).
 * - A Twilio Account: https://www.twilio.com/ to get your Twilio numbers and API credentials.
 */

/*
 * Installation & Running the Application:
 * 
 * 1. Download the `main.exe` File:
 *    - Get the `main.exe` file from the provided link or folder.
 *
 * 2. Running the Application:
 *    - Double-click `main.exe` to launch the Twilio Call Scheduler.
 *
 * 3. Input Twilio Numbers:
 *    - Enter up to 8 Twilio numbers into the designated fields.
 *
 * 4. Input Target Number:
 *    - Enter the phone number you want to call using Twilio.
 *
 * 5. Save Twilio Numbers:
 *    - Click the "Save Numbers" button to save the Twilio numbers into a `twilio_numbers.json` file 
 *      located in the same folder as the executable. This ensures the numbers persist between sessions.
 *
 * 6. Run the Scheduler:
 *    - Click the "Run" button to start the automated calling process, which will schedule calls for up to 10 hours.
 */

/*
 * Usage Instructions:
 * 
 * Save and Load Numbers:
 * - Click "Save Numbers" to store the entered Twilio numbers in a `twilio_numbers.json` file. 
 *   On restarting the app, numbers will be loaded from this file.
 *
 * Monitor Call Status:
 * - The status window displays real-time info about scheduled calls, including the number dialed and 
 *   the time of the next call.
 */

/*
 * Configuration:
 * - The app reads and writes Twilio numbers from a local `twilio_numbers.json` file. This file will 
 *   automatically be created the first time you save numbers. It will be stored in the same directory 
 *   as the executable (`main.exe`).
 */

/*
 * Twilio Account Setup:
 * 
 * 1. Sign up for a Twilio Account: https://www.twilio.com/
 * 2. Get your Account SID and Auth Token from your Twilio Console and ensure they're configured in the script.
 * 3. Purchase and verify your Twilio numbers for use in the scheduler.
 */

/*
 * Troubleshooting:
 * 
 * Numbers Not Persisting:
 * - Ensure the `twilio_numbers.json` file is in the same directory as `main.exe`. Saved numbers should persist across runs.
 *
 * Calls Not Initiating:
 * - Check that you’ve entered valid Twilio numbers and that your Twilio account is correctly set up.
 *
 * Internet Connection:
 * - Ensure your internet connection is stable for Twilio API calls to work successfully.
 */

/*
 * License:
 * This project is open-source. Feel free to modify or distribute the code as needed.
 */

/*
 * Contact:
 * For any issues or questions, please contact:
 * - Tiffany Aquino
 * - Email: tiffanyaquino116@gmail.com
 */
