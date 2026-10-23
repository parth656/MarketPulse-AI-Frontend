# MarketPulse AI — Frontend

A frontend repository for the MarketPulse AI project. The associated project documentation describes a retail AI learning application covering analytics, machine learning, forecasting, sentiment, retrieval, and API-backed demonstrations. Confirm the pages and backend integration in this repository before treating each workflow as implemented.

## Scope

The frontend should provide a clear entry point to the available demonstrations and explain what each model page does, the inputs it accepts, and the limitations of its output.

## Run locally

The repository appears to be a frontend-oriented project. Inspect the root files to determine whether it uses a package manager or is served as static HTML. For static HTML, a simple local server can be used:

```bash
git clone https://github.com/parth656/MarketPulse-AI-Frontend.git
cd MarketPulse-AI-Frontend
python -m http.server 8000
```

Open http://localhost:8000 and navigate to the entry page. If a `package.json` or build tool is present, follow its scripts instead.

## Integration

- Document the backend URL and expected API request/response schemas.
- Keep private credentials on the server; do not ship them in frontend code.
- Handle API timeouts, invalid input, empty responses, and server errors.
- Make it clear when a page is a demonstration or educational example rather than a validated production model.

## Accessibility and quality

- Use semantic headings, keyboard-friendly navigation, and meaningful alt text.
- Verify layout at mobile and desktop widths.
- Show loading, error, and empty states.
- Add screenshots and test important navigation links.
- Keep claims and metric labels aligned with actual backend outputs.

## Status

This README is a project-level guide. Verify the current page list, exact local run method, and API endpoints against the repository before deployment.
