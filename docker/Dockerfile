FROM debian:bookworm-slim

RUN apt-get update && \
    apt-get install -y \
        qt6-base-dev \
        libgl1-mesa-glx libglu1-mesa \
        vulkan-utils libvulkan1 \
        libxcb-xinerama0 \
        libx11-6 libxext6 libxrender1 libxrandr2 \
        libxi6 libxcomposite1 libxcursor1 libxdamage1 \
        libxtst6 libnss3 \
        && apt clean && rm -rf /var/lib/apt/lists/*

WORKDIR /hailbox

CMD ["./box"]