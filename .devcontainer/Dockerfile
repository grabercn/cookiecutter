FROM python:3.10-bookworm

# Set the working directory
WORKDIR /workspace
COPY . /workspace/
RUN rm -rf .devcontainer

# Install the required packages
RUN pip install -e .
RUN pip install tox
