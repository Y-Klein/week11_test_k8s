FROM python:3.10.19-slim-trixie
WORKDIR app/
COPY requirements.txt .
RUN pip install -r --no-cash-dir requirements.txt
COPY . .
EXPOSE 8501
CMD ["streamlit" , "run" , "main.py"]