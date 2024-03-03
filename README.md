Eco Racer User Authentication with JWT Token Refresh
This module enhances the Eco Racer user authentication system with JWT token refresh functionality. It utilizes JSON Web Tokens (JWT) to manage user sessions securely. When users authenticate, they receive an access token and a refresh token. The access token expires after a short period, while the refresh token remains valid for a longer duration. When the access token expires, users can use the refresh token to obtain a new access token without having to log in again. This mechanism improves user experience by reducing the frequency of login prompts while maintaining security standards.
