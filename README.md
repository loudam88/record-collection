#Record Collection

A vinyl record collection database for enthusiasts geared towards the artistic side of album cover artwork.
This application allows a user to keep track of thier record collection to a digital format. This will allow them to create, add and delete thier collection and allow them to add comments for each entry.

## Important Links

- [Deployed Client](https://louisdamico.github.io/record-collection-client/)
- [Client Repo](https://louisdamico.github.io/record-collection-client/)
- [API Deployed](https://intense-scrubland-71825.herokuapp.com/)

## Planning Story

The first stage of the planning process was to create a wireframe and an Entity Relationship Diagram for this application.  In this process I was able to set expectations on what I needed to accomplish, along with a realistic timeframe in which to do so.
Next I set up resources and materials I would need in order to complete the project. This consisted of organizing all the martials and setting up documents for quick and easy access, in a flow that would be the best use of my time.
After all these are completed, I then set up my file structure along with any dependencies I would need to get started.  Once they were all ready to go I then created a new repository in which I pushed up the main branch of my application.  Now I was ready to start developing!


### User Stories

- As a user I want to sign in/up
- As a user I want to Create a new album
- As a user I want to search for a single album
- As a user I want to sort the collection
- As a user I want to add comments to the album

### Technologies Used

- Mongo DB
- Ajax
- JSON
- Node.js
- Mongoose
- Expresss
- Passport

### Unsolved Problems
- Still need to add imagaes for each album and store them.
- Would like to add a more input fields with a drop down menu and would like to add user notes along with a personal rating system per album.

### API End Points

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out`            | `users#signout`   |
| PATCH  | `/change-password`     | `users#changepw`  |
| GET    | `/albums`              | `albums#index`    |
| POST   | `/album`               | `album#create`    |
| PATCH  | `/album/:id`           | `album#update`    |


## Images

---

#### ERD:
<a href="https://imgur.com/y6hB5IF"><img src="https://i.imgur.com/y6hB5IF.png" title="source: imgur.com" /></a>
---
#### Requirements:
<a href="https://imgur.com/Quh4WNj"><img src="https://i.imgur.com/Quh4WNj.png" title="source: imgur.com" /></a>
