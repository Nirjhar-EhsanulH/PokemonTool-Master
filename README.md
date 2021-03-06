# About
This is an application to visualize Pokemon data is a simple way for the purpose of generating user logs so that we can mine logs to understand how people use visualizations with multiple views.
Original repository link: https://github.com/arpachuilo/PokeVis.
This is a modified version of the original repository.

# Requirements
### Redis
  - Windows https://github.com/rgl/redis/downloads
  - Linux/OSX http://redis.io/topics/quickstart

### Node
  - Windows https://github.com/coreybutler/nvm-windows
  - Linux/OSX https://github.com/creationix/nvm

# Usage
### Starting up
1. `npm i`
2. `npm run redis`
3. `npm run server`
4. `npm start`

If these steps do not work, follow the steps provided in alternate README. 

### Pulling Results
The command `npm run dump` will output logs into `logs/data.json`

### Cleaning DB
To clean the DB you need to restart the logging server that was ran using `npm run server` then you need flush redis which you can do using `npm run flush`
