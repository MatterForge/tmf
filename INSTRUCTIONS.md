Serve to localhost:8080
` python3 -m http.server 8080

Find the Process ID (PID) using the port:bash
` lsof -i :8000
Kill the process
` kill -9 (PID)

Start Aider
` aider --model ollama_chat/gemma4:latest