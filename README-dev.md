
## Backend development environmnet 
use Python version 3.11
source .venv/bin/activate
pip install uvicorn
# or install all backend deps
pip install -r backend/requirements.txt

start debugging using launch.json job "Python: Backend (uvicorn, debug, with reload)"

backend is running on port 8080 (http://localhost:8080)
swagger http://localhost:8080/docs

## Frontend
use node.js version 20
create .env file copied from open-webui/.env.example
set CORS_ALLOW_ORIGIN='http://localhost:5173;http://localhost:8080'
npm run dev

frontend is running on port 5173

## Connect to Gemeni models
add openai connection : https://generativelanguage.googleapis.com/v1beta/openai/.
api-key: AIzaSyCqMnTMVEIJVW8dF8HGVwJiir1kRm14xvI


