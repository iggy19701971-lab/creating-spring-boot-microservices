FROM mcr.microsoft.com/devcontainers/java:1-21-bookworm

# Yarn is not needed for this Spring Boot project.
# Its APT repository currently has a signing-key issue that breaks apt-get update.
RUN rm -f /etc/apt/sources.list.d/yarn.list