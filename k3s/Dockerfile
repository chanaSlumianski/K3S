# Use an existing docker image as a base
# FROM pandoc/core:latest
FROM pandoc/latex:2.14.0.1

WORKDIR /k3s

# Copy the Markdown file into the container
COPY ./describingK3s.md .

# Set the command that should be run when the container starts
# CMD ["pandoc", "-s", "describingK3s.md", "-o", "output.html"]
CMD ["pandoc","describingK3s.md"]