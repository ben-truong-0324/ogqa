# ogqa

git add .
git commit -m "added grahping libraries for nbs and pyarrow for parquet"
git push -u origin main

uv init
uv run src/main.py 

# uv run will replace python run

uv run jupyter lab