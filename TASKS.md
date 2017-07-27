# Tasks
This list can be used to see the progress.

## General
- [ ] Extend documentation.

## API
The tasks regarding the API layer. 

- [X] Setup repository/project.
- [X] Setup initial project files/structure.
- [ ] Create endpoint to return trending repos.
- [ ] Create API documentation.

## Datastore
Tasks regarding the datastore.

- [X] Research which database to use. (Fow now we go with MongoDB)
- [ ] Use own deployed database or a existing service.
- [ ] Document database models.

### Scraper Worker
Task list regarding the scraper worker which will collect all the data for the 'trending' module of the api.

- [X] Setup repository/project. [Link](https://github.com/RolfKoenders/gitpoint-api-trending-scraper)
- [X] Research (Proof of Concept) scraping of github trending. (Using [cheerio](https://github.com/cheeriojs/cheerio))
- [X] Scrape all the possible data.
- [X] Setup data model for the collected data to store in the database.
- [X] Insert data to the database.
- [X] Make configurable using environment variables
- [X] Use [Cron](https://www.npmjs.com/package/cron) for the cronjob pattern
- [X] Dockerize
- [ ] Add tests
- [X] Update documentation

## Deployment
All the tasks regarding deployment, envrionments etc..

- [ ] Setup dev/test environment.
- [ ] Setup CI/CD to test environment. 
