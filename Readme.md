
Authentication API v2 introduces auto-expiring tokens.
Tokens are valid for 24 hours and must be refreshed.

Token generation:
POST /auth/v2/token
- Requires API key + secret.
- Returns access_token + refresh_token.

Rate limits:
- Max 100 requests per minute.


(Automatically updated based on latest context)