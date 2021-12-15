FROM python:3.9

COPY requirements.txt .
RUN python -mpip install --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt

RUN pip install bashplotlib
RUN apt update && apt install sqlite3

CMD ["/bin/bash"]
