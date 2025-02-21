# WhatsApp Chat Analyzer

WhatsApp Chat Analyzer is a Streamlit-based web application that provides insightful analytics on WhatsApp chat data. It allows users to upload their chat export files and visualize various statistics, word clouds, emoji usage, and more.

## Features
- Upload a WhatsApp chat file (`.txt` format) for analysis.
- Display key statistics:
  - Total messages
  - Total words
  - Media messages shared
  - Links shared
- Identify the most active users in group chats.
- Generate a **word cloud** to visualize the most commonly used words.
- Find the **most frequently used words** in the chat.
- Analyze **emoji usage** with a pie chart visualization.

Check out the live version of the app here:
WhatsApp Chat Analyzer

## Installation

### Prerequisites
Ensure you have Python 3.10+ installed.

### Clone the Repository
```sh
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### Install Dependencies
Create a virtual environment (optional but recommended):
```sh
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```
Install the required packages:
```sh
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```sh
streamlit run app.py
```
2. Upload a WhatsApp chat export file (`.txt`).
3. View and analyze various statistics and visualizations.

## File Structure
```
whatsapp-chat-analyzer/
│── app.py              # Main Streamlit app
│── preprocessor.py     # Data preprocessing functions
│── helper.py           # Helper functions for analysis
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```



## Known Issues
- Ensure your chat export file is in the correct format (without encryption).
- Some non-English texts may not be processed accurately.
- `emoji` package may require an update if certain emojis are not detected correctly.

## License
This project is open-source under the [MIT License](LICENSE).

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.

## Author
Developed by **Neha** 🚀

