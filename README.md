# mini Google Docs

Technology used:
- Quill
- React
- Node.js
- MongoDB

TODO:
• Shared document editing, in the style of Google docs. The system should support real-time editing and
viewing by multiple participants. Multiple replicas would be maintained for fault tolerance. Caching
and/or copy migration would be useful to minimize application response time. [as in [requirement](https://www.cs.cmu.edu/~dga/15-440/F12/p3.pdf)]

## start the app

create a `.env` file in parent folder, and add `MONGODB_URI=xxx`, which can be configured using [MongoDB Atlas](https://cloud.mongodb.com/v2#/org/6715ca4ab96d2b062465b35b/projects).

start the client: `npm start`

start the server: `cd server` and `npm run devStart`
