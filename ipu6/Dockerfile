# Use non-ipu6 custom Fedora Sericea base image from this repository
FROM ghcr.io/lukejcollins/fedora-sericea-docker-build/sericea-custom-build:non-ipu6 

# Install the ipu6 drivers from the rpmfusion repo
    rpm-ostree install akmod-intel-ipu6 && \
    rpm-ostree cleanup -m && \
    ostree container commit
