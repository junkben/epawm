# epawm

Example Python Application With Microservices

## Trying it out

A `run.sh` utility is provided to handle starting the FastAPI app. Currently, only development mode is available. Here is what you would expect to see:

```console
$ ./run.sh
++ uv run fastapi dev --host 0.0.0.0 --port 8000
Bytecode compiled 1529 files in 178ms

   FastAPI   Starting development server 🚀
 
             Searching for package file structure from directories with __init__.py files
             Importing from /workspace
 
      code   Importing the FastAPI app object from the module with the following code:
 
             from src.main import app
 
       app   Using import string: src.main:app
 
    server   Server started at http://0.0.0.0:8000
    server   Documentation at http://0.0.0.0:8000/docs
 
       tip   Running in development mode, for production use: fastapi run
 
             Logs:
 
      INFO   Will watch for changes in these directories: ['/workspace']
      INFO   Uvicorn running on http://0.0.0.0:8000 (Press CTRL+C to quit)
      INFO   Started reloader process [11002] using WatchFiles
      INFO   Started server process [11216]
      INFO   Waiting for application startup.
      INFO   Application startup complete.

```

The links provided by the console output should function properly.

## Techstack

- Python 3.14
- UV: Package Manager.
- FastAPI