# OpenAI Article Summarizer

[DEMO](https://summarizer-sigma.vercel.app/)

##### OpenAI article summarizer is a web application built with ReactJS, RTK Query, Tailwind CSS, and the OpenAI GPT-4 API. The purpose of this tool is to save the reader's time by providing a summary of an article instead of having to read the entire article.


## Table of Contents
- Features
- Getting Started
- Usage
- Contributing


## Features
1. Paste the link of an article to be summarized.
2. The tool will utilize the OpenAI GPT-4 API to summarize the article.
3. The summarized article will be displayed within 10 to 15 seconds.
4. Responsive design using Tailwind CSS.

## Getting Started

#### Follow these steps to set up and run Promtopia locally on your machine:

```sh
git clone https://github.com/Vasyl-Pavlenko/summarizer.git
cd summarizer
```

#### Install Dependencies:

```sh
npm install
# or
yarn install
```

#### Environment Variables:

```sh
VITE_RAPID_API_ARTICLE_KEY=your-rapid-key
NEXTAUTH_URL=http://localhost:5173
```
 Replace your-rapid-key with your actual Rapid [KEY](https://rapidapi.com/restyler/api/article-extractor-and-summarizer).

#### Run the Application:

```sh
npm run dev
# or
yarn dev
```

The application should now be running locally at http://localhost:5173

## Usage
- Open the application in your browser.

- Paste the link of the article you want to summarize into the provided input field.

- Click the "Summarize" button.

- Wait for the tool to generate the summary, which typically takes 10 to 15 seconds.

- The summarized article will be displayed on the screen.

### Contributing
We welcome contributions to Promtopia. If you'd like to contribute, please follow these steps:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and ensure the code lints successfully.
3. Submit a pull request with a clear description of your changes.
