# Smart Home Simulator

An IoT smart home simulator built with Python (devices), C# (server), and React (frontend).

## Project Structure
- `devices-python` Simulated IoT devices (lamp, thermostat, fridge)
- `server-csharp` ASP.NET Core Web API for central control
- `frontend` React dashboard for device management

## How to Run
1. Start the server:
	```bash
	cd server-csharp/SmartHomeServer
	dotnet run```
   
2. Indítsd el a Python eszközöket:
	```bash
	cd devices-python
	python smart_lamp.py```

3. Indítsd el a frontend UI-t:
	```bash
	cd frontend
	npm start```