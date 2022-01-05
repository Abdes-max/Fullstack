# ==========Version local==========================
# FROM node

# WORKDIR /app

# COPY package*.json /app/

# RUN npm install

# COPY . /app/

# EXPOSE 4000
# CMD [ "npm", "start"]

# =========Version prod======================

FROM node

WORKDIR /source/Fullstack

COPY package.json /source/Fullstack

RUN cd /source/Fullstack && npm i --only=production

COPY . .

EXPOSE 4000
CMD [ "npm", "start"]