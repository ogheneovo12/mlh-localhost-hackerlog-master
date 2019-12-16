# MLH Localhost HackerLog

This app demonstrates setting up a simple NodeJS / MongoDB application to be deployed on Azure. If users have the password, they can post log messages with a chosen name. Posts are sorted in reverse chronological order and paginated.

## Configuration
Aspects of the app are controlled by the following environment variable. Feel free to modify them once deployed or before running locally.

| Name  | Description  | Default  |
|---|---|---|
|  PORT | The port to run the webserver on | 3000  |
|  PAGE_SIZE |  How many log items to display on each page in the application |  10 |
|  MONGODB_URI | URI to connect to mongoDB instance. Usually automatically set using this variable on most providers.  |  mongodb://localhost:27017/hackerlog |
| HACKERLOG_PASSWORD | The password to post a log message | P@ssw0rd! |


