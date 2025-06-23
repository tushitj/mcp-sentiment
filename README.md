# MCP Sentiment App

A sentiment analysis application for processing and evaluating text sentiment.

## Features

- Analyze sentiment of text data

## Prerequisites

- [Python](https://www.python.org/) (3.10 or higher)

## Setup

1. **Clone the repository:**
```
git clone https://github.com/tushitj/mcp-sentiment.git
cd mcp-sentiment
```

2. **Install dependencies:**
```
python -m venv venv
source venv/bin/activate
pip install "gradio[mcp]" textblob
```

## Running the Server

```
python app.py
```

The web interface will be available at `http://localhost:7860`, and the MCP server at `http://localhost:7860/gradio_api/mcp/sse`

## Testing the Server
You can test the server in two ways:

Web Interface:

1. Open `http://localhost:7860` in your browser
Enter some text and click “Submit”
You should see the sentiment analysis results
MCP Schema:

2. Visit `http://localhost:7860/gradio_api/mcp/schema`
This shows the MCP tool schema that clients will use
You can also find this in the “View API” link in the footer of your Gradio app