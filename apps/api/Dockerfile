FROM node:20-alpine

WORKDIR /app

# Copy root package files if we need them for workspaces later
COPY package.json .

# Copy the API package.json
COPY apps/api/package.json ./apps/api/

# Install dependencies in the API directory
WORKDIR /app/apps/api
RUN npm install

# Copy the rest of the API source code
# (This is useful for production builds, though dev volume overrides it)
COPY apps/api .

EXPOSE 3000

CMD ["npm", "run", "dev"]
