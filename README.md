# Rails 7 app with Helper Widget + Turbo Integration Test

A minimal Rails 7 application created to test Helper widget integration with Turbo navigation.

## Purpose

This app demonstrates how to properly integrate the Helper chat widget in a Rails 7 application using Turbo for client-side navigation. It serves as a test environment to verify that the Helper widget persists correctly across Turbo page transitions.

## Features

- **Two test pages** with giant square buttons for easy navigation testing
- **Helper widget** configured with Turbo-compatible initialization
- **Debug logging** to verify Turbo events and widget behavior
- **Minimal setup** for easy deployment and testing

## How to Run

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Start the server:**
   ```bash
   rails server
   ```

3. **Open the app:**
   Navigate to `http://localhost:3000`

4. **Test the integration:**
   - Click between the two pages using the giant buttons
   - Open browser Developer Console (F12) to see debug messages
   - Verify Helper widget appears and functions correctly across navigation

## Expected Behavior

When working correctly, you should see console messages like:
- `🚀 Turbo:load event fired!`
- `📦 Destroying and reinitializing Helper widget`
- `✅ Helper widget reinitialized`

The Helper widget should persist and remain functional as you navigate between pages without full page reloads. 