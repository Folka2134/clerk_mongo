This is a backend template for Clerk authentication and Mongodb connection. Including the synchronization of user data via the clerk webhook

Steps:
Setup a clerk and mongodb project
Visit- lib/database/index.ts and update the "dbName" to the name of the mongodb db
Create .env.local from .env, add aquired keys
Deploy project
Create Clerk a webhook endpoint using deloyed URL + project route.ts directory - {URL}/api/webhook/clerk
Update .env.local and deployed site with the new webhook signing secret key.
Redeploy is nessasary
Create a user
