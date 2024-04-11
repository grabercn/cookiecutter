FROM python:3.13.0a6-bookworm

# Set the working directory
WORKDIR /workspace
COPY . /workspace/
RUN rm -rf .devcontainer

# Install the required packages
RUN pip install -e .
RUN pip install tox
