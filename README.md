# My University Buddy (MUB)

## Prerequisites
- Node.js (v18+ recommended)
- npm

## Install dependencies
```sh
cd apps/api
npm install
```

## Run the API server
```sh
npm run start
```

The server will start on http://localhost:3000 by default.

## Test the Hello endpoint
```sh
curl http://localhost:3000/api/hello
```
Expected response:
```json
{"message":"Hello from My University Buddy API"}
```

---

For more details, see [docs/spec_001.md](docs/spec_001.md).
