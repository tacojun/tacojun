# tacojun

I build small Python tools and React applications, and improve them with tests, CI, and reviewable changes. I use AI tools to help with development, then review and test the resulting changes.

## Duyuru Kontrol

A local Python command-line tool for checking Turkish announcements before sharing them. It validates dates, ranges within the same month and year, weekday consistency, and an optional Unicode character limit. Missing years must be supplied explicitly; it has no runtime dependencies.

CI covers Python 3.11–3.13, including wheel and source-distribution installs in separate clean environments.

[Usage and examples](https://github.com/tacojun/duyuru-kontrol#readme) · [Tests and CI](https://github.com/tacojun/duyuru-kontrol/actions/workflows/tests.yml) · [v0.2.0 release](https://github.com/tacojun/duyuru-kontrol/releases/tag/v0.2.0)

## Flask Chatbot

A deterministic Flask demo for exploring a browser chat interface and a JSON API. Replies follow fixed rules; no external LLM is used. The server and browser share a message limit measured in Unicode code points. If sending fails, the browser keeps the message editable so it can be retried. Input validation and a health endpoint make API behavior easy to inspect.

[Source and local setup](https://github.com/tacojun/Flask-Chatbot#readme) · [Tests and CI](https://github.com/tacojun/Flask-Chatbot/actions/workflows/tests.yml)

## Portfolio Website

A React project for presenting an introduction and selected work in a responsive single-page layout. It uses plain CSS, with accessible section navigation and project cards linking to repositories. UI tests cover the main heading, navigation, and project links. The README explains local development and production builds.

[Source and local setup](https://github.com/tacojun/Portfolio-Website-React-Tailwind-#readme) · [Tests and build CI](https://github.com/tacojun/Portfolio-Website-React-Tailwind-/actions/workflows/build.yml)

I use issues and pull requests to document and review changes. I am interested in practical open-source developer tooling, including Web3 infrastructure.
