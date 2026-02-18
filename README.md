# pre requirments 
python -m pip install uv
python -m uv init .
python -m uv add fastmcp


# if faces fastmcp not recognozed problem 
delete .venv 
python -m uv sync


# run 
python -m uv run main.py