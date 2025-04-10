# 🔒 Security Best Practices

## Sensitive Data Handling

### ✅ Good:
- Store sensitive data like API keys in `.env` and ensure `.env` is excluded from version control.

### ❌ Bad:
- Hardcoding API keys directly into the codebase or committing `.env` files.

## Sanitize User Input

✅ **Good:** Always sanitize user input to prevent XSS attacks.  
❌ **Bad:** Using unsanitized user input in the DOM or API requests.

---

## Use HTTPS

✅ **Good:** Ensure your site uses HTTPS for secure communication.  
❌ **Bad:** Using HTTP, exposing data to man-in-the-middle attacks.

## Avoid Client-Side Authorization

✅ **Good**: Perform critical authorization checks on the **server-side**.  
❌ **Bad**: Relying on **client-side** authorization checks alone.
