# Upaya delivery api

This is an unofficial python package for integrating [Upaya](https://upaya.com.np/)'s delivery system.
You can contact them for any kind of support. I contacted them for API documentation for my own purpose and they gave it to me.

I will be creating this project without complete vibe coding to learn about python package deployment on pip. I will be using web version of Claude to learn about some steps, but won't be using Claude Code at all or any other automated agents.

## Setup

- Get your API Key from [Upaya's dashboard](https://delivery.upaya.com.np/).
- Set it as an environment variable in a `.env` file or any other place (like database table).
- Initialize the class as below

```python
client = UpayaClient(api_key="YOUR_API_KEY")
```

## Dev setup

I've used [Python Poetry](https://python-poetry.org/) for package management. It's a really good tool.

### Using Python Poetry

- Install Python Poetry using their [docs](https://python-poetry.org/docs/#installing-with-the-official-installer).

I will add more steps later on.
