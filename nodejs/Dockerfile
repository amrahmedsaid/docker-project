# File: hello-world-node/Dockerfile (docbuc/hello-world-node)
FROM node:23.1.0-bookworm-slim
ENV TZ="Europe/Amsterdam"
COPY server.js /src/
USER node
CMD ["node", "/src/server.js"]