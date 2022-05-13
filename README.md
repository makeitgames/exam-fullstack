# Exam Instruction

## Objective
Build an NFT marketplace web application similar to [Opensea Explore Page](https://opensea.io/assets) with limited functionalities.

## Architecture
We need only 2 components for this exam, Frontend Application and Backend API.

Frontend Application will be served from static web server and running on web browser. Then it will interact with Backend API via REST protocol. 

Backend API will be running as another server waiting for request from Frontend.

## Preferred Tech Stack
- React.js
- Node.js

## Getting Started
1. Fork this repository as your public repo, and start from there.
2. Create Backend API:
    - Use REST as messaging protocol
    - Use JSON file as datasource
    - Provide endpoints to list, view, and comment.
3. Create Frontend Application:
    - Make it a SPA and Responsive
    - Use any CSS framework as you wish 
    - Provide screens to list NFT and show item details with user comments
4. Create `installation.md` and write instruction on how to run your application.
5. Submit your repository url once your work is ready to review within limited deadline.

## Expectation
Our NFT marketplace must allow users to:
- Browse items by collection name
- View item in details - description, seller, and price
- Leave comments on any items

## Bonus Points

- Additional features like Favourite items
- API documentation like OpenAPI spec
- Unit Test or Storybook Snapshot Tests 
