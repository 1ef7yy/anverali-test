include .env

PORT=$(SERVER_PORT)
PYTHON=$(VENV)/bin/python3
HOST=$(SERVER_HOST)


runproject:
	$(PYTHON) manage.py runserver $(HOST):$(PORT)

reqs:
	$(PYTHON) -m pipreqs.pipreqs ./ --force