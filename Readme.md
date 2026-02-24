
The Authentication API v1 uses a token-based system.
Tokens never expire automatically.

To generate a token:
1. Send a POST request to /auth/token
2. Include your user credentials.
3. The token will be valid forever unless revoked manually.

Rate limits:
- Max 20 requests per minute.


(Automatically updated based on latest context)