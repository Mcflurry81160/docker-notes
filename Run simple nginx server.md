To run a simple nginx server locally and test that Docker works use the following command:
```
docker run -p 5000:80 -d nginx
```
This will download (if not already in the machine) the latest version of the nginx image from the Docker hub.

#### Getting a 403
If a 403 is received when trying to go to http://localhost:5000, make sure that the port is not already in use.
If this is being used already, use a different port like 5001 for example and go to http://localhost:5001.

This should show the test page that nginx serves.

