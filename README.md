# Voice-Activated Railway Ticket System

A fully voice-activated railway ticket booking system designed specifically for visually impaired users. This application operates without button interfaces, relying on speech recognition for input and text-to-speech for output.

## Features

- **Completely Voice-Controlled**: No buttons or visual interfaces required for operation
- **Booking Management**: Book, modify, and cancel railway tickets using voice commands
- **Ticket Viewing**: Search tickets by name, ID, or view all tickets
- **PDF Downloads**: Download tickets as PDF files using voice commands
- **Accessibility-First Design**: Designed specifically for visually impaired users

## Voice Commands

### Main Menu Commands
- "Book a ticket" - Start the booking process
- "Modify a ticket" - Change an existing reservation
- "Cancel a ticket" - Remove a booking
- "View tickets" - See your bookings
- "Look up ticket ID" - Search for a specific ticket
- "Search by name" - Find tickets by passenger name
- "Help" - List all available commands

### Ticket Viewing Commands
- "All tickets" or "Show all" - Display all tickets
- "View ticket ID12345" - View a specific ticket by ID
- "ID12345" - Directly view a ticket by just saying its ID
- "Download ticket" - Download the currently viewed ticket as PDF

## System Requirements

- Python 3.11 or higher
- Required packages:
  - streamlit
  - fpdf2
  - pandas
  - numpy
  - pyttsx3 (for text-to-speech)
  - speechrecognition (for voice recognition)

## Installation

1. Ensure you have Python 3.11+ installed
2. Install the required packages:
   ```
   pip install streamlit fpdf2 pandas numpy pyttsx3 speechrecognition
   ```
3. Run the application:
   ```
   streamlit run app.py
   ```

## Voice Recognition Notes

- The system will automatically listen for commands without needing button presses
- Text input activates only as a temporary fallback when the microphone fails
- When asked for specific information (name, age, etc.), speak clearly
- For station names, speak the full name for better recognition

## Accessibility Features

- All interactions are available through voice
- Text-to-speech feedback for all operations
- High-contrast visual elements (maintained for development purposes)
- Large, prominent download buttons
- Clear voice instructions for downloading tickets