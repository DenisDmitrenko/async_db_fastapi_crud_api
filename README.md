pip install fastapi sqlalchemy[asyncio] uvicorn[standard] alembic aiosqlite

**git** init  
**git** add .  
**git** commit -m "Basic structure"  
**git** remote add origin https://github.com/<addres_to_repo>  
**git** push -u origin master

**alembic** init -t **async** alembic  
**alembic** revision --autogenerate -m "first revision"  
**alembic** upgrade head  
