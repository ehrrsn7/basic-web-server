# Python Flask Web Server

This project mirrors a basic Express.js server using Python Flask.

## Setup Instructions

### 1. Create a Virtual Environment

Open a terminal in the `python_flask` directory and run:

```sh
python -m venv venv
```

### 2. Activate the Virtual Environment

On **Windows**:

```sh
venv\Scripts\activate
```

On **macOS/Linux**:

```sh
source venv/bin/activate
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

### 4. Run the Server

```sh
python server.py
```

The server will be available at [http://localhost:3000](http://localhost:3000).

```
PS C:\Users\eliharrison\Code\basic-web-server\python_flask> python .\server.py
 * Serving Flask app 'server'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:3000
Press CTRL+C to quit
```