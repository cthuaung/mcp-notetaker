# AI Sticky Notes

A simple application to keep and manage your notes using AI.

## Setup

1. Clone the repository
2. Create a virtual environment using uv:
   ```
   uv venv
   ```
3. Activate the virtual environment:
   - On macOS/Linux:
     ```
     source .venv/bin/activate
     ```
   - On Windows:
     ```
     .venv\Scripts\activate
     ```
4. Install required packages:
   ```
   uv pip install mcp-python
   ```

## Usage

Run the application with:
```
python main.py
```

### Available Features

- Add notes
- View the latest note
- Summarize all notes using AI

Notes are stored in a local file (`notes.txt`) in the root directory.

## Project Structure

- `main.py` - Main application code
- `notes.txt` - Text file containing all saved notes
