FROM node:22-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=5000 \
    DATABASE_URL=mongodb://studynotion-mongo:27017/studynotion \
    CLOUD_NAME=dzu1jfwfo \
    API_KEY=789135622294595 \
    API_SECRET=DU6-m9NivRwc66NTmTUCRxr-hdc \
    JWT_SECRET=b3d3TnM0bHpxeV82dFdxZ4NGRXMWZTY0pOb1hZVG9IYVRydFZlR0l1dw \
    RAZORPAY_KEY=rzp_test_RFE8xrOcO7aXXY \
    RAZORPAY_SECRET=LqVngD4lI0GLQvpGbx1dzw8r \
    FOLDER_NAME=Studynotion_demo \
    MAIL_USER=do_not_use.me@yahoo.com \
    MAIL_PASS=kvzistqyzdnneqmn \
    MAIL_HOST=smtp.mail.yahoo.com \
    MAIL_PORT=465 \
    MAIL_SECURE=true

EXPOSE 5000

CMD ["npm", "start"]