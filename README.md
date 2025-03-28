# AI-Affiliate-Automation

🚀 AI-Affiliate-Automation – The ultimate AI-powered affiliate marketing platform! 🤖 Automate lead generation, outreach, & sales with AI chatbots, email marketing, video ads, & smart analytics. 🎯 Boost conversions, save time, & maximize profits effortlessly! 💰 One-click automation for affiliate success! 🔥 #AI #AffiliateMarketing

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/AI-Affiliate-Automation.git
   cd AI-Affiliate-Automation
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. Start the production server:
   ```bash
   npm start
   ```

## Features

- AI-powered lead generation
- Automated email marketing
- Video ad creation
- Smart analytics dashboard
- One-click automation for affiliate success

## Troubleshooting

If `npm run dev` is not working, follow these steps:

1. Ensure all dependencies are installed:
   ```bash
   npm install
   ```

2. Check for any errors in the terminal output and resolve them.

3. Verify that the required environment variables are set up correctly. Refer to `.env.example` for guidance.

4. Clear the `node_modules` folder and reinstall dependencies:
   ```bash
   rm -rf node_modules
   npm install
   ```

5. Ensure you are using the correct Node.js version. Use a version manager like `nvm` to switch:
   ```bash
   nvm use
   ```

6. If the issue persists, try running the server with additional debugging:
   ```bash
   npm run dev -- --debug
   ```

7. Check for open issues or report a new one on the [GitHub repository](https://github.com/your-repo/AI-Affiliate-Automation/issues).

8. If you encounter the error `Module not found: Error: Can't resolve './src'`, ensure the `src` directory exists in the project root and the `main` field in `package.json` points to the correct entry file.

   - Verify the project structure:
     ```
     /workspaces/AI-Affiliate-Automation/
     ├── src/
     │   └── index.js (or main entry file)
     ├── package.json
     └── ...
     ```

   - Verify the `main` field in `package.json`:
     ```json
     "main": "src/index.js",
     ```

   - Ensure the `src` folder exists and contains an entry file:
     ```bash
     mkdir -p src
     touch src/index.js
     ```

   - Add a basic entry point in `src/index.js`:
     ```javascript
     console.log("AI-Affiliate-Automation server is running!");
     ```

   - Restart the development server:
     ```bash
     npm run dev
     ```
