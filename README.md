# PocketSmart AI – Smart Budget Planner

PocketSmart AI is an AI-powered budget planning application that helps users manage expenses and receive personalized recommendations for home interiors, parties, and jewelry purchases.

## Features
- **Home Planner:** Suggests furniture, lighting, and interior items based on budget.
- **Party Planner:** Estimates expenses for venues, catering, decorations, and entertainment.
- **Jewelry Planner:** Recommends jewelry based on budget, occasion, style, and optional outfit images.
- **User Authentication:** Provides registration and login.
- **Recommendation History:** Stores previously generated plans.
- **Shopping Links:** Connects users to external shopping and service websites.

## Technologies Used
- Python and FastAPI
- HTML, CSS, JavaScript, and Jinja2
- SQLite and SQLAlchemy
- Google Gemini API
- JWT authentication
- Pytest

## Installation and Setup

1. Open the project folder in VS Code.
2. Create a virtual environment:

   ```powershell
   py -m venv .venv
   ```

3. Activate it:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

4. Install dependencies:

   ```powershell
   pip install -r requirements.txt
   ```

5. Create the environment file:

   ```powershell
   copy .env.example .env
   ```

6. Add your Gemini API key to `.env`:

   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

7. Start the application:

   ```powershell
   python run.py
   ```

8. Open **http://127.0.0.1:8000** in your browser.

## API Documentation

Visit **http://127.0.0.1:8000/docs** to explore the available API endpoints.

## Testing

Run the tests using:

```powershell
pytest -q
```

## Future Enhancements
- Live product prices and availability.
- More personalized AI recommendations.
- Advanced budget analytics.
- Additional shopping platform integrations.

## Conclusion

PocketSmart AI combines artificial intelligence and budget planning to help users make informed purchasing decisions, organize expenses, and find suitable options within their budgets.
