FROM python:3.13-slim
WORKDIR /dsai 
COPY requirements.txt hw3.py user_definition.py ./
RUN pip install -r requirements.txt 
EXPOSE 8501
CMD ["streamlit", "run", "hw3.py", "--server.port=8501", "--server.address=0.0.0.0"]

