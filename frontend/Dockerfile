FROM node:22-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ENV VITE_APP_BASE_URL=http://localhost:5000/api/v1 \
    VITE_APP_RAZORPAY_KEY=rzp_test_RFE8xrOcO7aXXY \
    VITE_API_URL=http://localhost:5000


EXPOSE 5173

CMD ["npm", "run", "dev"]
