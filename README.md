# uni-notice-board# University Digital Notice Board

A static website for COMSATS University Islamabad, Lahore Campus.
Built for DevOps for Cloud Computing course (CSC331).

## Local Setup

npm install
npm run lint:html
npm run lint:css
npm run build
docker build -t uni-notice-board .
docker run -p 8080:80 uni-notice-board