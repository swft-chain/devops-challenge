### Setup and Launch

Run the app using the provided scripts:

```bash
chmod +x setup.sh
./setup.sh
```

Ensure you configure `.env` from `.env_example`.

#### Development

- Run in Dev Mode

```bash
npm install
npm run dev
```

- Build and Run

```bash
npm start
```

## Project Structure

```
test-devops-orchestrators/
├── setup.sh           # Setup script
├── install.sh         # Installation script to set up and run on the client node
├── .env_example       # Set your INFURA_URL here
├── package.json
└── src/
    └── app.js          # Express server on port 3000

```

---

## Requirements

- Node.js 18+
- Bash (for script execution)

---
