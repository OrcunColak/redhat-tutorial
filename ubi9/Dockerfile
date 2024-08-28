# Start from Red Hat UBI 9.3 Minimal
FROM redhat/ubi9-minimal:9.3

# Update repositories and upgrade python3-setuptools-wheel
RUN microdnf update -y && \
    microdnf install -y java-21-openjdk-headless && \
    microdnf clean all
