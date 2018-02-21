# CryptaKings-API-Wrapper
Python library for wrapping Cryptkings API Service

## Implemented methods:
1. OAuth Service:
   - `auth_get_token` - request for access token using credentials
   - `auth_refresh_token` - request for refreshed access token
2. **User** resourse:
   - `user_create` - create new User with the given credentials
   - `user_get_all` - read all Users (requires access token)