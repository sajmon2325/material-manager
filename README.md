# Material Manager #
Web application for managing ang keeping track of materials and tools used for 3D printing
and electorinc components used with IO boards (e.g. Arduino, Raspberry Pi).
Application will be split into two components
- Frontend Web GUI
- Backend Web API

This project contains frontend web ui that makes it possible to visually keep track of all
materials and components mentioned above.

## Application Arcbitecture ##
Frontend Application is using React and Vite and will embedded in docker container with all
its dependencies. Backend Application is build with Nest.js and it is using MongoDb.
Similarly as frontend application, backend API will be hosted inside docker container

### Main Features in v 1.0.0 ###
- Ability to add, update and delete all materials and el. components
- You can define a project and link all needed materials and el. component it will need
- You can track how many resources you have spent already and if you need more of them
- After finishing a project, view the overal profit / loss, and resources spent
  on a current project
